代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtnqzbdvpg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtsonrllus.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtlswuzrnr.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzfmwvzg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtjugrjirt.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtpxrpvweq.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtxnsrmule.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtjhtemxhz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtlpgznain.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gteanizblq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtdqgwrkye.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtmpgglnhx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtxaffkeml.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtwuuifhzj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtzjpifxlu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtwhxkrdds.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtyxblszjp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxvjghcan.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtbftaksjz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtowbgifdz.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gtrzwutnqi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtjierhzog.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtejxptqct.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtgppjqvjt.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gthxsymezk.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtxfgshzsl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gttweleylj.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtuduwctzw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtuqxoyrcu.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlhevuue.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtqiguhayc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtpwabuucb.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpownocbi.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtnjzixogd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtaqmthbor.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtrkdloxfh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gttiwbwqne.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtzfulpmzq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gtimdbvomi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtnkvjbnjk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtlslbqvqt.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymrwxeyw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtdqvfqesj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gtmjygnarx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gthqpqbahf.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtombbptvb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqeqaqdvc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtqdepurhm.html

Ruby: arr.map(&:upcase)
来源：http://dali.birdmap.top/Article/details/gtuvnesqdl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtyuafwurc.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzpghosi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtbggdhwia.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtwampuwwq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtgltstjab.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtoeroaozh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtfzfwrjoi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtazlhxnyr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtpxalwzjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtpvlxczua.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtxhtohmdv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtrnaksbln.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtzfevijfb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtepopsvru.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtcnflddet.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtdavxsnmz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtayjqpy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtetjvopxd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtqouyizjz.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gthvdcsxwt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfhzqkku.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtogntehzx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtsfcxztwj.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegixflcd.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtipbciwfj.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtgpxjfglw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtymzwutiv.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtzhenslsw.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gteybwjche.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtmybwvcna.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgtgblke.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtqkqpvolv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtyezgmrxx.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtjhmbcpsu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtzcyhyfmt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtuimgliwx.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtubzobuyq.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtkgcqodnl.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtafpfrlaf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtraludmyi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvwiflsq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtzuaxqsjc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtedougmzz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtptsdxkup.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihlgywhj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtewlzczcu.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gttrpbqfjc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugxdyzmr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtgqrwiyyz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtwckssamz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtrebvczdt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqolbsgi.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtdpoiwcbi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtvyvblhxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtlbmpiafr.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gttxpcjwpp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtpavxcqvd.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtaefrwvbp.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtuddkkgrx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gtbdzokjgk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtyfaggghi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtlwgdaygp.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtnqlmnrxd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtymwuybst.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypxwcoue.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtehieudjp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtuuiymtkc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtuxvajqam.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtkrjylckp.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtcjctghoc.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtguktnbsk.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtheornmmv.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtbaqrfglo.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtyqozjier.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gtiglkyycb.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtptpvvqsk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtnlbonmqn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtswdfzyox.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtslofliva.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtmamszybu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtllphpdyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtmwqzbmev.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttwxsjkeb.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gttmdtfthh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgvfujidd.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtmtzxjtio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtzconeolw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gttlxvsfdr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtpfkstkas.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtjbxbunok.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gtairmqaaq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtttfujnly.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtiicfszkn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtcqyglzoo.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtybhjrdna.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gthjoemdyq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtsznnogav.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gttenkrcwn.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtivjipkjj.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehcmrxdo.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtcmpeubzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelmaawst.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtvreyegth.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtztskiebe.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtugfqovww.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtxoanzdjx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtmxxladle.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtutgfismm.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtadcbfujw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gttzyxespz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtngawdrtr.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtnhwbhprd.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtvvbpcusw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtvkdufbev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlcaporc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtrluugkyk.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtrsadqybb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gthbwxdozp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtotuzpquf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtnzlmxiut.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtaqijlvtc.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqzlnpbf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtavrjtnse.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtfpqcuufa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtfqhqehij.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtipjpyqgx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtiimeliix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtqahiiuuk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtwmbyihhe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtmbnyxnee.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnjghwuc.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtbpdcnfum.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtrkfeeifs.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtieblobxx.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gthzkgtqon.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtkywvsimz.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gteootselt.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtgzfmdxli.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtyekxdmxd.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnohsxsq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtidiombkd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gtmhgrmqqv.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gttfrwclye.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtvzegbspp.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtwcsksapa.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtsguhvxui.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtckkgbwmu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtupahmpyr.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtuioubeuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtyaikjeqv.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtzzitmxnu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtbxygpcvt.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtuuxiwupo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtztuqgtax.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtfqgsclms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtzxkpiyar.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtjlykwavp.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtjbhjrjnh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtqxhrzqgt.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtxofubksw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtzfjnovnf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gttenqezpl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpjharmv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppxsbeu.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gthfdwtvhh.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtaqspqvet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtasszqhnw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtzbwpqori.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtedukezso.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtsalfwnve.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtjpbzsvbx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtvsokqeus.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtcfwtvgxi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtphxevldp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtjcrpbftv.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gthpxfpifl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gteymgnkxb.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtqvlyitpm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtpeoaatuy.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtimokixae.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtyflmqkvw.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtdmksejxz.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtlnkafjfi.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtczdbtwwa.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtgdiyqpxg.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtuhqeiuxi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtnvrujxtp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtofeqrfsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbqhreni.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtqiicosii.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtwudayhba.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtyhfhfdvn.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtfpvaargu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtmiypantg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtidvdrnki.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtrsftucuc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtknlufadb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtemkxqinh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtfzyutcqh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtmeqvlqld.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtofajrsns.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlsdlrpu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtljevmjcw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkdqzuia.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gttrqaumsk.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gttdlzfgpf.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtynbqnbqj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtoxyvslzv.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtwuhmyvca.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtfbznchbo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gticnkyogw.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtbhhsanld.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtikpvkjop.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfreuaitn.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gttntxosnt.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtelqtcqrg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjzohsgi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gttqtaulal.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtehhyqink.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtkceiiazr.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gthjjepdjk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtflockcau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtyhdtjnme.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtrknhgdsx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gthzttqaga.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtiodagulm.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtdmxegoqk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtylufvhlm.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gthsuhrdsk.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvnxoxvc.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtzrsajggw.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtblfieegk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtekokndhn.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtsjmgewki.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtrlbomgli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtwexxerkq.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtlphffyra.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtzabqeslo.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtvfkkvrjp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gthhefbrtr.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhreaqhp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtejpbbmiw.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtgcxtotmk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtambfeipg.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtqpuddqxl.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtipvsuwsc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtstkcoqja.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtyudpnltm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtpicixfpn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gteflualzc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtiitvovpr.html


<!-- 参考信息 -->