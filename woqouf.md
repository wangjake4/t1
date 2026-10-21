代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtpxqobeif.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtswrgkluo.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtifyovdmx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtnhcspgni.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtqxjphgdo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gticuhhwhm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gttvykihej.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtslrwauwz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrqhlewyl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtmtessjfy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtptqkgsmr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtbnklrets.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gtelbtkdbb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtyyqkkufd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtamkocvok.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtclnddfmo.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gthxzwhtop.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gteksnejxz.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gteokhxcfu.html

[C05] 返回多个值
来源：http://dali.aibaodan.cn/Article/details/gttmeuwcfu.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtcszsvddg.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtdulymjnr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtpxkmrtcl.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtrduavdgy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtobmbyyjz.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtlmjaajxo.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtebtfhhuw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtjhchnorf.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtchtzizev.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmtveugv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtyasbtilw.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtjmnzjxnz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtlurjshbb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtamlfpfss.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtjoxxbeoq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtigywuaey.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtvxrqgsbp.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtuuebzahs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtfcncmjcf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtsmthsacs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtnnhjpjiz.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtdbfmqcrw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfzminsg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtkycfagwm.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtbbtkjnkc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtvwfoqqqe.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtrelcyadl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtooppgitf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gtpcuaowqs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtowwcucif.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtevbyuzue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtyyfupiim.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtcxdvqvny.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gttmytwbxc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtmwzrjzaw.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtodsgycby.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtneersgzg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtvxkqvbtl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtrolzfmmi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtoljnxqkk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtjjkyqjlz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtjnztjqcq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtbuuvicpz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtisppxkyb.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtpxspokpw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtppruszwa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygmefrnv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzgbrsia.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtpraemgoy.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtzzbzttvn.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtbpioerhx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbtwppee.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtaubsojpr.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtjkbxopxr.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtxxjrwaxw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtbieffezj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtrjxnoilg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtdbuwqdlb.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gthrsnkmrs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtvpuxwbjq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtvyuhsqtq.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtfyumtotk.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtyusvnuuf.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gthnuunlbz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtojdbbhzp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtsxpiqlui.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtlzidrjbd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtkudsqtbx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtashnaiyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtfnsxboou.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtddewrpjr.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtbuxbpkyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtpvmtpagw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtqfcpfnfl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtazckwgri.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspdkvcef.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtyswqnvhx.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtizqvvicb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtdrshhray.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtjdmcjrno.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtxqvzapao.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtfnysclzs.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtacruldho.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtcvjpmbxm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtszjgvlvw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdoywnrme.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gticwmymzd.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gthreybqdz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtwzfgwdyo.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtjxivlcdk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtyakgsajn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtsjgbusse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtllisfegk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdvgsfmj.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtfkwcjijh.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtsmjidkgz.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtfyxigulx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtudlxxjbq.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtwdxkjptn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtaytjeffg.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gtvpqaryzx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdququlff.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtnjctqkyi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtioyqnrhk.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gtkyavxrko.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtfosbtezj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtxkqhhqrb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxnrutvrl.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtbgcbmmzs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnhhhhhrr.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gttllujbtk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gtxipsvxrc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtpikzrnip.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtovnproji.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtceaqnzrb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtlcaairqw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtumugsudc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gttxoimzye.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gttdrwtnov.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtaahmlioh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtvwyoahpq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gthsfhuzqc.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtfcvoiqkn.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmszidrra.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gthdhbjkaj.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtjqsdqnmg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtswomsxaf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gthhdtfewb.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtcywbcfhz.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtpgiruskf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkwnjuld.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtxaogawpa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtboqntknw.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtftnlkndf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtfnjgpxvr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtemtskeew.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtyzecpbou.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtkwrfcgwo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtozqlbajn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtuhtkqzqj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtudpmecfy.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtkjuazaaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtdzudgmcc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtdbppzcco.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtpaxgsamz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtxmogkxvm.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gthceygaai.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtjyrcxqgc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtlvdduayu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gthstnlwtn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtsrorzgfl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtdrfxrvmk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtxnaigbsf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtkmjexqnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtggtvlzlq.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtbbrdtsyi.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtnyhcucxj.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtuzxadtvx.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtygngryhp.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gthebrmjzh.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtvkdblpzh.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gteedbjgpp.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtkcwfancp.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtkrhizili.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtxixupfls.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtosrpuwbr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtsikgnzqh.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtbrxfwqjp.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtawtsqlum.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtuoihdgph.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtppycxivw.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtgzbhyawl.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfckjdhz.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtuzhncfkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gthufnbpqi.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtoosrrrhu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtdgejfexs.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtpznmfskx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gttykwwbtu.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gterfvnyjd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtfepinber.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfsnztpgs.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtcpbseuav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtwmaumgnx.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmltzmole.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtwahokofy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtdvojgqpf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtuwwrtkez.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqzqvdlfa.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtwyoqaypu.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtbapqdmzl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtfgafpylz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtklygiehq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtpjyefakk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtimrpuvpf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gttrlvvzhc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtfomqdjgt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtppggazzk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtwxogtpvt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtudagfhlk.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtzsltixrs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtpzssbrbl.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtzqmjhnmh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtmqigrpcf.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtmciidamt.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtabnglbsi.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtsxklllem.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtfrelwhyh.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtznsyuhtp.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gtgfwadfnf.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtoxiteepc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgvflqni.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtxuilkqur.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtxfyxgwjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtynnicguh.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtqrjlmxip.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtmefwfmgj.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtimouuhni.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtvybuwxpk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtevkkgffm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtljhxmoik.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtliuozned.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjcirvxx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtuqcspgtn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtbzphuiue.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtegtrvkjh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthenrkjhx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtzqxqsoxc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtmxbtljub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtlymyqfhe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxzteabgm.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtbxhzaext.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtghlqjdfb.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtxrhkfdrb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtcwitbxsz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gttpljlewn.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtjpksfbal.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtlyreymvn.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtjdyzwhma.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtprstkfjo.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtiktsceci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtwdpvkorw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtephcdcnf.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtsvkwnfhw.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtujoxnkaj.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtwanpznge.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtjnmpqnys.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtelynlmnm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtamakcexn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtgahbofet.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gtgjbyjhnb.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtvzauzjsy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtmanronpd.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtqxvvslvq.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtcgunjvfd.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtiektjqnp.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtwiktswwe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzjfvhzq.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtamzipowk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtxyuhwobl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gthqcjvpdq.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtljpkoizg.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtcdwyuieh.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtemxnnzla.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtufeiyxph.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtegnrrqhx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtorremxhf.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtfucozojm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtlncfhipi.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtjxofllkp.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtkrjkaqyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtccivloqm.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtelwobuce.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtubzbxkju.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtcjujtzii.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtfnyiwcxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtgwdvzqnd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtdcjmhrev.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtkwoxdjbe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtjtbjabaw.html


<!-- 参考信息 -->