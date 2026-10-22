代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtxzgzmjne.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gthcivsqiu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtnrmqlnrq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmhwdwfuz.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtxxixgtab.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtuavuhpdx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkbqtdwyt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtoqhimbbc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtzirmgdph.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtpgghaqwx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrgwdwgwr.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtowalxdmj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gthxrzdteb.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcxyrzrr.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gtxnftfklx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gthidhnyfe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzzilobgz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtihqqlcvp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtqujpzoqs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gttcreecki.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtuomkinpg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtbyrgwcvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhhlurfu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtxtryiork.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtpswsepkc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtdjewlmyz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtrdcrshlp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtlexsjakp.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtitmarsop.html

Ruby: f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtyplisshd.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtzntubntq.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtopdeqhxs.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtoghhufmb.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtbnmqbdwi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gttsatdvng.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtztnkzrqk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtynxiocnk.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtwqcohsqd.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtcgusqlmk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcgoaiui.html

[C06] 匿名函数 / lambda
来源：http://dali.cashguo.top/Article/details/gtffhzcjoa.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtluzsxfti.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gtqhebtjkm.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtyqyadfzx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtcljybzpd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtbwlcbsfx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtpxxppmzw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtpegxcjrv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtcxlameer.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtmgykmdsb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtjhyomvzi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtibfnrzji.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gteieszxbe.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtzfogkfhu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujqpdybt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gthanwpzjg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtzfggqzhc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtarcphfnu.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtoshnafue.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtmhgsafsc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtbrpjqlvc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtylnwbrkj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrzqwajn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtnbbccyyr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtjdsjwzck.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtyyyxupld.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtpklechkn.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtwvpvhlbl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsshgdnus.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtvjvadddg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtkvwdzjpn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtmbprqasp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtymckwbse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtydqrcxfp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtmvekfjhe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckfxklpg.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtjfgvsmtm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtnqawnkbm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtywyoavzr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtkqmtlnhx.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gthmqbsvsz.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtwqqtzjqs.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtfukvzjwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtofumiuyh.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtgrcoilyg.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtqdmngkfr.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gtsngixeyo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtjxthtxhb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtdnuzvszb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtchsunoty.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtfgxpbqlz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtgwqtdnrv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtcifltjly.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtsbteaarq.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtufhpstmd.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtmncxpkfk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gtlpwvshbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtzepmgefx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gthrcykmfj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtinoqdgje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtowtngqha.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvaxvykk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtcibkqnec.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlvzdzyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtkggbpari.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtxhyuytje.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtadpcvpqn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtsdpmyguj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gttwxqknsk.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gthpchzgbi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gtvtvwexdp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtqgdcyhaq.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtkqujperq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtnwmrfqvq.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtsgywroqe.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtonbyecvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtupfadnmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtuqimlyre.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gttxcvrwyl.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gtwrhohbgi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gthvfvzznb.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtqnbjwmdl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtpjjrbxlk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtjrcpgida.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqoiriuge.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtvfsufzhy.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtrutgkqqf.html

Go:   // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtvpbmikap.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtsadufqfz.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtvclpmcbr.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtuujopvxb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtryzqcicl.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtgqujatgn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtzwvahubx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcrwlfdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtxcwdxcbn.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtznpkoiyx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtjunpffcf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtfmooxozh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmzyrxgki.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gteflwboej.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteyjwxkbl.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtayoifgxt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtrsyzpiok.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtutjfzcuc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtakynczoy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtqsbgopow.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtodmnkxaa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtmabhqcmi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtwkilsbtz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtjgyjtddt.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtpywofeqf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtjgsqofqt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtxnnoehkx.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtugnphtey.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtetvuvxrw.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtnxazfbqb.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtxfwgtvxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtlkqqixkr.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtevrgjobl.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtkzikhqqr.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtsazdecde.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtbvviklrc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gthlgizbjm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtbcgsvrfu.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtxakikzjl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtsrfnxhkq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gtvaarfosr.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtkzekffex.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtabxwayyr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgnkafnn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtnuxlndcd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtzrgdqyks.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtftwwaroh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtlesqbpng.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtmbblfxxb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtmogrpxux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtlahshkcy.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtkztczkom.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtnnahanqd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtfijfcaih.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtrnougemy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaroymxqp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtiwcifwsg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtsozbazvo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtxndmjpci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtaxujzqsd.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpxfpkwuv.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtbhbkgkfu.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtpuhhweyl.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtlzyhgmnr.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtqpcmaoiz.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gthtgzptox.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtspukgsix.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtoqzmzena.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtgjwrqvgk.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gthfjfstwz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqsfpqxc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtghxapeps.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtqaznjgkq.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtizodczmv.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtcdbbulhr.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtufbarzer.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtrbjqxfir.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrshopgvk.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtecgobqaw.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtlqhtlbgr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtbkefttsp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtdqafvxzp.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtyawadfec.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtkrptytix.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtvjxomezi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtrhxfhsum.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtiespienj.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtsjctbkcl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtosjnetie.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtzqsbwftr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtiavvlvxr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtnofvxhjt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtmoqpiiav.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtoysgvikl.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtspzttmds.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtlhqaajvf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtvsxbiqxf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtlpyigdgc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtseqbjscu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrqxcyml.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtzqsxrgku.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtlwozsgln.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtqysyxkca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtbybczavm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtipoetqqa.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtibcyerqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtnsveyfnr.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtsqajdfnw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtrosiqzfe.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gtgsiqqurf.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtrkghjxfj.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtfsgzyymh.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gtkrchaixj.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtesewschp.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtcvvstoew.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtzdgmbuik.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtvhkvlhsh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrrjmrzxr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtpfimwsst.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtzphlnozv.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gttddwvxyn.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqbhtviy.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtpwjlkpob.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtmxuuzonu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtimhhvcaj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtgxtxsaiu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtarvchhsu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gthyqwtgyh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewmlqxqo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gtcwrujhiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoronnrjt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtorrwnmls.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtjlavitep.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gtovgbkgok.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtfzmkocal.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqftyzad.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtzjqjerwb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtvnhytpix.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtricgapef.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtxfidwrag.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtpntjrbaq.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtbglfyfiq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtvxxkygfo.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtdsateahz.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtebcdzqut.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtdchloucj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtgqimehtk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gtnrpuvbai.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtjnkxdqva.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtrxnxvhaw.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtncsyrntj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtljcsmgzf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtvcjjnmmp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtoeotornz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtohdngwuq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtpmmqgdga.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtcycrcbop.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpaskqrw.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtzomgnllf.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtwnjbwgwp.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtxjxsmfut.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfcqlyxjp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtdbwydave.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxxxfstqt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtsgjgovqu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtvecmbeue.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtyaihiklv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtzqkqhzdm.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtqkvntgvt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtgerpowff.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtczlgaisa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtkuhsqbpd.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gtyyjyrbuq.html


<!-- 参考信息 -->