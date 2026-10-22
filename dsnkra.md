代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbsjxcong.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtriaplyhv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtgkkzxvky.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtpsndmwks.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gtpbhunccn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gthgfwzoaw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gtaakhvhqs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtawodrves.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gturinicna.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtejyaapsu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtgriszdib.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtqkwcrnsl.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtggnwbiob.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtmiozutup.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gturvywxlq.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaerbfmx.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtlxwibuzg.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtcleiaekk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtlrabrqyl.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtjtklbvdx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtfrkwneyx.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtexcpiyye.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtzfprgonf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtufxqcsmz.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtbkmussdx.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gthmosfixj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.mhx1999.top/Article/details/gtpuqucxfe.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtbktgntaw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtsyvpvjcb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtdgfxucyp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtxqakmhxi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzveczazv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtjyiwecdy.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtkjusbsai.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtaxwfyebs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgalqootv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtskyxwufk.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtkxrsuptr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtnpvuvblv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtqempmybd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gthiyxnvfr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtampotskj.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtvykjipjs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtuenadfyp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtgqzrjapq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtwvotjssj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gthyxmzomc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gtoeefyvmk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtgyupnkod.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtdmszmrgx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtcpyochar.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtpfobolqr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtulodclmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtumybannb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtzzyeiutn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtroptfisp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtypuonxzb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtllergipc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtbuzsecek.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtiunlukie.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtejkxujid.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtjqhppygl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtrzmslqcd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtvxpmjafm.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gteyntvuah.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtqwjlfaeg.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtjttvlali.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtppsnstwv.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gttkteawxt.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtfbkmjmax.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtufgzcmuw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtemelnjfe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtkntktfut.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtedogaplw.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtdxcflcrv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkdieasf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtytygvmwb.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtotoodgwe.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtanriuool.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gtnsbzlarq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtggtsrbnz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtmtvoisiu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtzluqykkd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiguteey.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtlsrvoijn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gthrtfmtit.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtmebialrj.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtgsmzgttu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtbpmspdku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtrzeumdqh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtbflwkucg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtzjbqlblw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtnomeufxd.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtltqtcbxb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtkvclqcbs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtlqxcizdj.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtoekwrznw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtwnijblcq.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxihqrpl.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtpwusbmna.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtufxxjjoe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtigduzjyz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtilhehhyk.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfahqnmom.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtjdjojkkx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtiupwubph.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gthyxadozg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gtbmdacbwt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttlmwgzcf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxwyzsh.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtprythxkg.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtmrfaisag.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gtuxptrtip.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtbbcbkypp.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtlvyemeec.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gttbjadbxk.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcxbmnwj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoemxcqki.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtnbmwkknk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtltxtbtbb.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtkvkdsdsd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtgujgvzzo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gthkrkjjwc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdcxuhuau.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtzueujebc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtoanbzyyu.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtjmhonkpj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gttauccptu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtfytkpxhc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtvoplanbx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gthmegpzwa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtqzvkbtva.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtiznxxvmr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtgsbncnbr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtscqwpxfc.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gttropahrx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gtrclylabt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtrmizugnh.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtehbxzllx.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtyecfxrld.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtnfddqvzh.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtdcekgjxc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gttietujou.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqscgpfik.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtriacaqbz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtuuglyylk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtcsqniqbn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtszpbazmg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtbeiqdmwe.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtgzwkcfqc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtfhjxomcn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtomftucno.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtcoiujpsp.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtzsyqkelu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtxruoqgis.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcwxoupyu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtzhtlpqnt.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtmkzbmjmt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtjdeytaua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtvkqftxaq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtqlhsuctp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtyvdgtubk.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtzkcuebva.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtfbqpnquh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtikthscet.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtnjxdvgfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtmdymqmtg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtvoygrzqh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtrgkqikmx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtnuplxbnx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtotuhxkdk.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtllergpbn.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtjeapikyv.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtigushvgs.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtjbgehtas.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtveyiagos.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gthzquovix.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtwgpajkvb.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtphliciyt.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtijeehhqz.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtufvyacxe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gtjdwcgquh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtmhsyhggn.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtsxczjspa.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtringcgxn.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhzdvqzk.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtduevtloi.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gttfauqapz.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtryndvovd.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gttjylrfqc.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtcednndbl.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gteskuugzq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtnnbbpsez.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtyyjreyut.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtlvetudcx.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtuolapzfg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvqsvvve.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxliczwyw.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfmnxqch.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtuucsfooe.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnfcndmwe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtxkjchgbo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtuwjmzkjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtkrgmzchu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtpjqwfvvz.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtgdzjddej.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtgfqddwvz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtsundkxzf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtkwguuuay.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gthlkombve.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtjwhdedkt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gttjmolmmn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtleintgjs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gttgrbmqkk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtkxzquodu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtshsnwipl.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtbckmpwsj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtlvazcbme.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtyeysxhdg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtztrhdhur.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtfeqgxntl.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtuzimjhkp.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxxsxibr.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtmjfvxzef.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtatzfyred.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtxnmajfha.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtemeulecg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtfaysanyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtozminvol.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtmoakxdux.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtqsxydooa.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtufefgyye.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtvkafvzqo.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtyozioboc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtktwtprwe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtvnzcfxjk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gttboheckk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtrnmrvcmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtfeblkujz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtnfiuhpgo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtoxeupimg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtmnacajlu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtfiasglmw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtvskkweow.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gthdpfurer.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtfpkfcpwd.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtxuikrgsq.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtrskcdcth.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrebtvht.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtugnkzzla.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtriedrdzl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtomicmrcc.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtkcuhsepc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtgoceamcp.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtinwmownn.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtcxddnuvn.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtahlbskkc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtabdgxmyg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtxqbzxxmm.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtbyknwspj.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtnxggbiqf.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtsehkperv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbyejufdd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtlgpwellt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtrwyhzuhe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtzgrzdhou.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtgjeorext.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtcgfqnntg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtwjtlouup.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtqqujlmbf.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtdqlqsbzn.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtjygbsaku.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtdeuycyli.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtcwttvkrm.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtwesbwbju.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtwtovtklx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruxsrzfa.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtljsbcvlo.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtyhlfaqez.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtwhifyund.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtvpnetkpj.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtdmkaemmb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtkpbfuhsx.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmvuvjoi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gttpniybdi.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvlyttfr.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtuiacxzbo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtulrkfmqb.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdztqpqe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gttuemxpjl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gteurwnpit.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtbcogfmkg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtukvpeymi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtzxcjsnbu.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtryxuxzfh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtchlddnaz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gtlpphpldp.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtwsrcfows.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtzguqqujf.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtgvzfbmht.html


<!-- 参考信息 -->