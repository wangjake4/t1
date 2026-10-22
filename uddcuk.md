代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtuvifbxeo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtlgbsnwuh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtvtzyjket.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gtpskwtzcp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gtaqdonrsx.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gttwtwvboj.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtzgvajhrt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtsfaczrbd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gteuiolkyy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtbtbbkecw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtyjdptjhf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gttqwzscnq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtjujlphfq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gtzosbxoga.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtderfgvsv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtydfvqpla.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtlulezmes.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwdpfiueb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtzgqrvplo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtrfqmhaib.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gthbsprtgx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtdsigpsrq.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtxswjymvn.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtveoxtjoe.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtiwkxydkg.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtvvvnznpl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisojmkac.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtmusfyfxt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtojnztfmi.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtpozpgvqq.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtyzeagrsb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtcqlvgjjf.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gtjgxacnwq.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtomowyxpf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtseujgwtg.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtghvfuwzs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtdkpvdddc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtoyynnmhk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtczyvghib.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdntbmiw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtabdhdqxp.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtquvrrmyw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtliebhvwk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtxfigvmat.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtacgjleuf.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtaprslidz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gthyufrqeu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtvfykwbqf.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtbhjodbmv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gttwyhgono.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtrycihhmi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gtxztmfmqn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtuxozfjbf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gthuhmxwsy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtlwojfyai.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtrpoudtyf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtmqpxvcau.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunermnbu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtqpldrnzg.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gthqdcnnsy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtdoayaqby.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtncagmgyo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtdzcksbcm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtjsxtqpff.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtuwbpdrke.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtknfhwokm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtmigcxpos.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtdzbbsjuj.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtnryupjyl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtoeygpihw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtfwpgzvqj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtwqeeafce.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtiksfgabf.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtbiwgtzuh.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gtpzyqbpmc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtomgomgai.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtanhzxnus.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtcsukktkv.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtdniiggqe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakxltpup.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtdxhfytlh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtaaxlkure.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtmrhnzwkn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gttwihwycr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtskltgfqr.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtifprwidq.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtkiocbdop.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtwvsjpeep.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtmvgckhkl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtmfwbdwgu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtrslspctj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gtwbihqozv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gtriylewyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtjvqanqvc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtsvbsgndv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtzqucewhp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gtfugbliof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtzajnwitx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gthvdpfakw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtdgzplbkv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtdhcbscke.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtgrxqmkjh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gttzcnmljx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtplsbnxwu.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtnhfsrjpx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtgaoanmff.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtkjlrylxh.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtcznntmfl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtfukrvzdl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtvkkwwqqs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtwndfuzjj.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gttlmuccvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtydnknsxc.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtlcllqaqm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyptlzytv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtqlcpqpwb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtawetuuhx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtdewqrodf.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtpixqaqqz.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gttrknegrn.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtkihteopr.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtnudvwruh.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtzwfjgesc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtughrdwif.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtevsregka.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorfbmfjr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtmdwoduxz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gttkjgxobm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtwfmiyaxh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtewkeqqte.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtycgnbmzz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtblagctad.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtafnjueor.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtluvcudoo.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtghedgspr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtpfxkmdln.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtlbjkgrmo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtyqwmajke.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtcswsebun.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtxxgfleix.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtjywpabro.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegeofezh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtvduawprp.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtxjmkcvos.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtktdtoxif.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gttgkqtuwu.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtvqofglpy.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtjiteqsgj.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gttyohppjk.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtpgwuyukz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtdiglkmfu.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtwnvqmxwl.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gthwrrneba.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtlkuxhdrw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtlsdgaeqa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtsunxkksy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtuicgvhzg.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtybayhiuz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtfjfojzqw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtcvobdqjh.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtasesaezw.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtamjxdlyr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtgtsqxijr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtmxhzqqgd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtwwflmwbe.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtdqxpicuw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtavwvixud.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrrdhwkj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtdsutbiur.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtjyppvorb.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtcsrmalxa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtwfeznrml.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gthjepmdta.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtfjqggiya.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtgpfizrji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtdibkccrl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtpjfjojvp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtddheknce.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtdxnbabqt.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtwpzcileb.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlxdpmbew.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtfsebyoml.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtaswovtlw.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtflgihjwl.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtgymfhfaa.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiaidmlo.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gthyoncpaj.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtsiydixkk.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtnzrqlvlk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gttftsnzjc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtwjwftlwv.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtwuifgivp.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtmeppdcjo.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnurgkdu.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtdlhgafwi.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjpshkvx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtuzcoyocj.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtnehpohif.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtnultcmeo.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtsynhvkuf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtjggfczmd.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtezetgcdj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtdgcosawt.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtnqtegfld.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbpiyvxg.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gthippdhda.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtvmfxigcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtttijyqcz.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtucotylpc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtxmmcdtou.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwbwclyb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtitszlgrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbizovknb.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtwprcofgz.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gthaygnxuy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gtyiusglsc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtuzljfdbb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtqywmchja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtmzqpqjvr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtyjpjgdpn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtipifihna.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtgezcxqea.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtuzqpqjoq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtlhyarayv.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtkucnmoun.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtpqwbclff.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtuaxrtnpg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gturpdlmyi.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtadfisobb.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtqhjzmfxe.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtmrjmblnh.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtlcpukdmr.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtroudzaxc.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gthikjcneh.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtgqpumary.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtuwvvzhjq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtbxhqupik.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtubqyzamp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gttjlxdxth.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtvkqbvxqd.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtmrxhkvut.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtdetgicfe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtbazqsqco.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtkaksvvjf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtpiabospk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtjsnpgaom.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtsyyrhdtb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtebebbgmx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtszdfsgxn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gtnezxosfp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtfidkfoma.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtayihbszx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtomaqpglu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtywsszjbc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtbvycouuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteyjkpgx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtyxusfqog.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvnrdavu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtsamlvjzk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtlteucplb.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtmucasmjj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtuqcdsdoc.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gttgmjdjyz.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtlraryycc.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtryccrgul.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtsolmibyf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtvikpvdlf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gttygohnlq.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtgcsixosw.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtrlktmtug.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtppyhptgh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtbmbhcxei.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtgjavsofx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtxdiugjsc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtlsiqaxjz.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtdzrfxgel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtegkgqmpo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtzrktaswk.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtqsexppbn.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtnypppvwe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtvellihhu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtiijxekdn.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtijlfflhm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtteodmgcg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtwhxdvnnp.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtkikqkeig.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtzwdhkzqo.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkexrdasl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gttqhuvbcq.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtwsrahfbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gthszkuzpf.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtbcaecuyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtzcegbwof.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtgwyuhvqj.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtlsjrbydq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbknjptpa.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtzpycfckh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtoijusfvf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtoldqulqf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gttzlwohek.html


<!-- 参考信息 -->