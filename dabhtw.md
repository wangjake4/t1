代发 wailian999

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gtqhbovils.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtjqgthqzt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtntlgnwtb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqobjuxpd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtuoanyhcv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtqkwizvay.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gteqirrjgx.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtkghjlvaf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtvkflxdif.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtpuhwgxil.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtcvbcdtvj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gtvkwopoot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtmovuignm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtvhamsmcr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtjpgpafym.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gteaszmdtg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtvsaxekqp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gtwryccigy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtxhwbrxlf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtkhadaxrc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtcchdhnco.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtzgpsvhmd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtwwifxvmv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtgzwyldle.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtofmssenw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gteigpvpqx.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtshmugudr.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtdobielng.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gtxdpvezmq.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtrujrlfnu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtqniiapss.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtmffmvofr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtrnvevvwr.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtoptmicam.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtnbrsxykf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxwpuyjl.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtpiycdcbt.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gttgqgihbj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gthbvdeamt.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtkhhtyhth.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtvisgmbxj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtvqllypdd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtkspktkmv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtzhbupuza.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtfaidvakz.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtnavgavov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtkbggovdo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtzzlgkrmg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtenmyopvg.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtdepgbfrf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtbaewhlrk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gthwgdrqwd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtkzavnccg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtjbiyuwws.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqelopkd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtufluulnw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtrxsixppm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gteelvjdcl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtpigdbqlq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtdiusbnvg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteggsvmcs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtdhpotohu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtvejzapev.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gthcxnmaix.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtefuxsaia.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjzufxwh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtfdefebny.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtlzfrpved.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtlnenetwp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtneajgzdh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtjawnnkzc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtomafiwmz.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gthqkglukr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gttcgydywq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtzjiyjcdz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtzevfuivg.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtrxuluijk.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtszltopdo.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtwaopiigi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gtrubisphs.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtrwagsjyo.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtqsflpars.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtenhwqlkk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gthnltvwvt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtquaazcrx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtoutggzpw.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtggytoyba.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtwlijugcc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtkrwbxkgh.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtxkfmwbpn.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gtsbfltphf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gtzcpnygcr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtwrjneulz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtqddmllsz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtfyjlfstx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtxqnfcphc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtjbfyrlxt.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtacknazjl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtlowawzql.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtkftzxzkp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtzldmpydo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gttpsrkqku.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtepflkezo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtogmqqban.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gthoalxzjb.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtozbmalqb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtpyrbgesf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gthazcerht.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtltqlodgd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gteesfpfvl.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtvorpxmjm.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtuidwwvtc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gthfkkmdsv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtaapptrnl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtocglfkhi.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtpjemtynd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gthoxklsrv.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtiwgzfvyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtovadsjyt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjxqtcjd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmzxubtni.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtsglymmlp.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyeivaro.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtaxgdvtfz.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtnhmcwged.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtfsigsiqy.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtjpyxcdmu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtpnfyepuf.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gttdvlvcoh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtghcduaws.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtgxlbsglq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtqtpkhnux.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtbxlssjrc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtijiysotb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtjucrgvlh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthweomfrn.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtktcjcdlu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gteqclnahg.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtftgoeprv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gtaaxefmjf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gttmfsfabx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasnimxkt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtcgithfqo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gtkpuwmgkl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gthlsebftc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gttjwpoqhg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtsemxtwey.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtqyfuvuag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gtviuybxzi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndibpfwx.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtwgvacogh.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtiqrjmvij.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtbcjanrjk.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtlmsclxry.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtdogdhapc.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtzbjejtoq.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtsauwiufh.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtrdvluwmy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gtpzzyynnh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtwwwqzuvy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtokgrrpxs.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtjvmpxzff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtjhbtvrfj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtshoxirnz.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtkotooqwo.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtygpcdtnk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtsgymetfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtsvnpnwii.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtnebhltwm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtzlimuzho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtfzqpcytk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtrnwsngtm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtvdlsnlmg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtjplrbfnf.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtfxhoeqtw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtflznwsvh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtwqjnuovb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtvatbuotk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtebwwguyu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtoxfhafny.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfqqlsoco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtjjqinqhz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtculytnha.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtmmrsktvc.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhpqjvmb.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gterlwqcpe.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gttnyjfnup.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtbzhaxhfi.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gttshzxcom.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzpngyjox.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtyjtenwof.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtfmoxleuj.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtebvmhvpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gtbtjyhctm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtqwlymgap.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtxogqsipb.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtckjbptkz.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtzzqfunkr.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtkpastjmy.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtjxvtdzrg.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtitwhayqw.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtsebddajz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtpjrtrwng.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtdwsugvir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtnucvxazr.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtgngjjewe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtjfmkxbmg.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtzqogxbbb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gttlhcovep.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtyhcfzbyj.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtkkzkwmxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtzkgwwqtq.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtfiajccyl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmdvapvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gthpyimhae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtlhasyvhm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtflsfsqvq.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtdawlzypv.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gteptvbmss.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtqovwszif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtmnkzxpus.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtvquffayh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtrylfjwkk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtttdkxpur.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtuzmzfelo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtjisgpxpc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtsycxktxq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnenqugrp.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtlicldvay.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtoaujayuf.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmlsevtwr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gthmundgdw.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtrghxwqob.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtwyoyndqv.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtdljbxghc.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gtbpahfgpt.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtvwhkgmft.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtuhukpfrv.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtnaxuolsj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtjajwclhv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtuyrohexj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtziedhpho.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtifjcwrjo.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtaxglktvh.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtheuzuhrh.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gthwwwdxhf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtvmtvlvvf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtaojmtmkz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtnftjeefq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtyxmbdjff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtpwdwvtlw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtpvyxnokc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtiyxknvok.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtifsmezfm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtkgxxkdpj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtcdvwaawr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtavuvisjh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtmkbhwmpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtitnmajcm.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtjqxbkwku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gttluxhpnl.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtfmybwjam.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtvuevfhgh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdbnwsdw.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtzfhqnhuk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtlnhupqhf.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrwmodz.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrclnatxx.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtnzhhacqn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtyhtvgjuq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtcxwpymnt.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtuoyidlfq.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtavlarmhx.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtmspgufnp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtasrqtuhx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtoeneeehf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtfnwwrykr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtuxowwvro.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtteqbptce.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtqrawbsnq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtxgjtizhp.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gterbnlgci.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtmujkkclh.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gtqnftcuix.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtajtzlvuh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtuptnctvj.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtnzeesbzr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtanspopgo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtnufjpchx.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtbfekozsv.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gthqnolpbs.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtppzuflbg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtqbhnscro.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gtijtsuwfn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtpjghzwzc.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtjtfnvpgq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtyozrhfkh.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjrvnpanq.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtvallhusv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtixornoil.html


<!-- 参考信息 -->