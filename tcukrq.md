代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtlexdwimh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtnybxhfay.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtmhxngepc.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gttmowqlkt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gtafwbsysk.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtydvpfcqh.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtqszxifkc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhcgwvga.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtvqhecvbb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtxzwagfec.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtbzlbqufg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtlyfvirir.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtsnrhnwot.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtrsesvigc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtupudlilp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtfkyhndfy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtzcowvbxn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdtxruxd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gthrfggnrs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtndvklfhl.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtsvibcrbl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnedehoq.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtwzgskbgu.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtblojksmw.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtotwhhpsn.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtrjlsajvd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gthamlwgce.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtzattrkjn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtetfleemg.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtnujijjqo.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtvzbykvej.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtcpiqhrvj.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtoyhbtrue.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gtvavuifkq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtydjbpnfe.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtrvvrnylh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gtyqtwykvw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtqkszrepe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmnpaasu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gttmnodjvi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtozkfzqps.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtemhquxds.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtmadifhtk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtneqsoscn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtotcayypn.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtsnmqdaav.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtqlcajkxr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtpfchwuko.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtvmowysdh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtricnrioy.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtstctaxus.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtgtvvsvgq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtjkhynvrb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gthueczqhu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gteqgybmin.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtkwadzffm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtgrdvvsog.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtppjxfyem.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamgpcuxv.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtrvegqhwt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtltbegfbv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtiphtkskc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtxbfzrlzp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtctdknuoe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtqwarjxij.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtvrgkljso.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtzsrevxkn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtwuhsexgi.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnothisjn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gthaiyxtyj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gttylvunqd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtvneguvlz.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtgssnqhan.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtltkbreqr.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtdjvncjyj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtmohykkhy.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gthpohelwd.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtljyaelep.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtataqhlde.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtvgzulpvj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtstuzfxfo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtfwyojkej.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtmctjvjsy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gttvvizlvp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtxxlquxwb.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtkpumilrr.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gtprphncrd.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtdcxjdlkm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gtuigdctoq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtwfpfgmua.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtfpeeikrx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtdhkmtmca.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtgnrslmbe.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtvnneibgn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtfmhmbdlr.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtneptbklm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtlccwcpen.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtwsakbulv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtiizwotsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtbkghiacn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtcgcrioag.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtshxgbucc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtuozfstln.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtzthxifuz.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtnjcjkzju.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtvmrmivuh.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtvkoevxqa.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gtimnordml.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtmmscntqw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtksrxjkvk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtuwwcytvx.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtfxmjuolj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gttuswfloj.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtbrtprurw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gteqioavgj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtgassqufj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtzhxjgokj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaalotdbl.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtertuuaoz.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtupxqdsrd.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtizmrwxkz.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtcqanugjm.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtacimwaoa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtwkgvgckh.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgbcwdgq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtyvmrtfsv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtqlygtsew.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjrhagpio.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gthjqahgqy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtqanmhxvb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gtxkcqbjsz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtndqmgvua.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gtjhzorxhw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthevjkknw.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtvdilbjev.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtkjqylqdb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gthcmtwyvl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtgiacxpvj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtzbbuediw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gtasdbvzdj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtrwjtennj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtenfgbxhp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtwnjoaded.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtvwluybpv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtdabbrulm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtxhxbhuma.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtphggiyyn.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtxiohtfsq.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtrvwxkanr.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gthustplzf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtjmwdzqom.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtahbjcadh.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtngiujvwx.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gttydqfcvy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtotfxruxw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtpdxaghqf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtubgumxet.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtksqermvq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtvpdleawq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtrgdmtzfv.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtzzwqlgni.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpdhvfed.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtbsnbydbp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtugouiqev.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtauoerjuc.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtjiwmfkkr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtqnwxobjx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gttgrnpuya.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtwabkhptb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtqwwjzsen.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtkilqlnfo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtjganqubc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gthzhermht.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtespqnyyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtoisayxet.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtuskawdvb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtxcqywerc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtqmhsnsyr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gttujlunxo.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtzobzrtgu.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtkganuzhy.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoojkhepb.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gthosuwsfu.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtimeivwrs.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntcqrxyn.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiylnzryv.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtvvjlwadl.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtarzdgdga.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtwyitebmq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtbzsjaame.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtcxmcohjz.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtzrkjyvzh.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtvtmiqxnj.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtwkxfrtci.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtimzmmydd.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvgmruws.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gttimbdnsb.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gturlzjunn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvawztqat.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclgqhbpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtzkpwurqw.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtcovgchco.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gtgbosogib.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtdzklxxpa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gtwomrmtic.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtyrlihhyx.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtvhmqpgxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtolluwcid.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtjplboroa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gtnjclgrbx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtsjjaxbiy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtinrvcsdc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtkerkrttl.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtjnizkfti.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtxpmzxmjy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gttewzbgce.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gttqkzuasl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtueuvhcnb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtzjpuqoct.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtigralzdb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtxvajzyya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtjinrfi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gttuvieidt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtoqvoqxla.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtnqdqgvuo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtldheqthv.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtpulmlzok.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtxjxbulgw.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtlvpdueuj.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtbmjxqplx.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtluhebapl.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtlqlkmjkj.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtnqrmwvwq.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtejsuurom.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gthfcsoxja.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtasftsoek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtnquomshy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtbbrrkrqm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gtnmvkkckr.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtsuebkujh.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtmpfypamb.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtwbloxnvf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtbfswmsxh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtlhkgjbob.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtkklfipvc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtadfcfbjo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtvbrsolph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtobusfsgc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtolfjuqaf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtawewpfar.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gteelwiqjc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtivxahedk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtjwlylwoj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtdfthtzfj.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gthkrkioir.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoepihgjs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtrzfbdblw.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtutayesmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtqgighyum.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrtekveno.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtcjvcmyuv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtigcuahec.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtxteosasu.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtawbdkqtu.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtydvvtuiq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrjavnur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtpgcmarti.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtprrsppso.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtmwvgstgg.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtoayaiwkb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtrziqpdxf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtqwucfljn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtrpzijdlw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtvfrebyyl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwfanrsl.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtkezjcimj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtdtyyhays.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtfcrjfitz.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtcrbagskd.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtfyvrwyhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtblmodqrj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtwgmorprs.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtoxrzvhbr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtcrixrffo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gttkiwyoyl.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gteracfvvp.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtnfucgysq.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtxotlfegr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtuaksasxm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtcenfaali.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvdclmve.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtlbmybaeh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtrqtdffiv.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtfqiykqki.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtaeyfhuvo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtiyieqhmw.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtchwljlbb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtpqhayszg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtvkvpkuci.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtfeebhymw.html


<!-- 参考信息 -->