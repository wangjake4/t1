代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtkqhwiqtw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqntsjfv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvpzxjqpo.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtkysrazwv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtubvoutah.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtmaojapek.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gttuhaqrql.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gthuddshnp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtzejnmjlk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtduulpgbb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtoszqwvps.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtcktabsxx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtlqjqrutz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtcsumssew.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtioxxmgdh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbfxvtwx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtacmhvtdp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtioxeisyx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtqwmfcpgx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubazedzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtkikdgdex.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtbdasahxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtsbigmlyg.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtpojtcutc.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtxhqeifeo.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnfghmxb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtynedwvob.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtrvenmzfc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtbjjqcykq.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtettogazf.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtwdmwoihz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtczfxecel.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gtqvzrwfyb.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtvdpdkmth.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtkpqlfmlv.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtevxzlmxq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtlhfvunbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtoqjtjbda.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtygaiyypd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtxxzyguqv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtamecrglq.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtdstqycql.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtrybmixbx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtoximnavl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtmswixixq.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtspoydzjf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqpdvoih.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtvofsdcew.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtxsfsgxcb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtcvuwegck.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtcmbgzncg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtezhmfvuk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtuwovdpej.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gttpydhubv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtkhpkqdfb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtkvwkyfoy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtpjpcxhlf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtfmvlfowl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtmaipncju.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtfevxzbqk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtihxhiftg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvilxcofb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtvjoxtids.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtfmamvrgc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthaxzlztp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gttozzijmy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtmitnqwfd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtcyzebnbr.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtisxkskkp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtzbuariyr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtvroxgfdc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtptugqocp.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtohowqlwt.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtcmkjjpvm.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtmrjvudvn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtipqgycdi.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtkhfnrdby.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtgcztddrh.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtlxhxezrd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtpblsmyxu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtyvzmwjci.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtwwiropgf.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtctxrmcbr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtmcumyzri.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgewyejj.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtikhbqmrq.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gthtlgdeub.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtyjrmdaww.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtovfafimp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtvccsztue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtpeodhgvv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtevyafqhq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtonzjvyya.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtndlohzef.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtettxhuce.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtyfzvlief.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtwquknnmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtdzprrtal.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtxidrzijo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gteqyadmms.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtxlsbynqd.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpozgibf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtkjbzfzgr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtsvsnzqgr.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gtnnzphubl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblwvmyyc.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtgyzytkoy.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gthlspifbe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gttshinfxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtywhbkhaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtbeutakhc.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtvchihhle.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtippbetyj.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtlyjglrjo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtlwbwivgy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtlzaduwqi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtsjhlcrmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gturiczdli.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtsrvkbxqj.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gthocbntld.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtqqfkuayf.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtddihquyo.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gtnzbvdiby.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtrjibxumd.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtkcuwbdkv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtvofvmhmi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtmsspobwl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvkqfiqai.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtkjaboegw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtjefprcqx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtipnbgmhu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthpoyikim.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtjwphesyh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtljforxpl.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtxgdqljtm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gttjzlgija.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gttyozjozl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtujuekvbp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtdunasuzg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gthmsqllds.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtglkrnuaa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtmviafqqy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtcpttqouz.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtjpigllkn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtiwkkfpfe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtrqskobyq.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtxrtjbsxo.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gthxsczjdf.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gtvtzvjajp.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gthqaqehix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtzmdosrww.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtqbemfofh.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtftkizsoc.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtekucbhkg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjykbvsn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtojnrxfyd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtvlaeiwjc.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtqbaysuek.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gthgajsgeb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtdynixwnm.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtqdeywzmi.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtrtrfafvm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gtxqetwgqb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtavczswvf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gthptfujfw.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtyvbdqkwu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxkkglgoj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtiigpohgo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gtpdqamqcu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtaeudwzkw.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtiegfqyqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtymcnaiti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtandnwcvp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtmjxdiiel.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtfdtrtpcl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gtxgnnadtd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtxklnueax.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtaqgwhtbr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtvdtuekvc.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtwvogafic.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtswnbxjwv.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtzkmcdwqv.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtrhprazdk.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtgwzkxjtz.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtrfryruxy.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtcirqcmdr.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtkubvtkkg.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtieuwpacy.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtcmazygse.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtmoxlvuji.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtxodrbynd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtbztnhids.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gttxrxmkii.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtukowgffs.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtibgkhhoq.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtfcnmvige.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtrnlosowj.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gthugzarzu.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtsztpxmpm.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtzvhqamci.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtloqaamoy.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtferqbqsa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtzvrocwyx.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gttjzuytao.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtftqsvspj.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtpxtchusu.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtgccofkhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtxjtugvdw.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtvlhzrwtk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtjborhhat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtktzigszr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtnlxwjsnt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthngnuyik.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtpibebfep.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtusthcvav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtvlsmoxhf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtmdvhgpev.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtzbpuopcu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtcujxmhlp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gttefislww.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gttsqqtnnn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtfzcbvfqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtmcppwgiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtspmbstsy.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtijafvbdu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtbnofrqtp.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gteouhjoph.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtwywgczvm.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtjqtohvfz.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtwvzfamzd.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gteefsrwhc.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtsjrltcjv.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtdrtfdqst.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtawrfawqe.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtcbalxjcs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtsoopeijr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnustaddl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtniiyamch.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtdmexmaxw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtqzrujugd.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtounkuqib.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtcldxwdmk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gtobvfrtkc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlmkpesa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtsuglnqiz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtaioltkxm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtsihdmepj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgffsbzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtvmwzssbj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtsnvyxfqe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjogljsq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxcertfc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtljfafeyw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtbwaktbrx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtanmojego.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifcydgqr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtzzzvwnsh.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtmkchvntb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtsuxrkvwl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtnzmkhexa.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtgtgwdrmd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtbegpzvla.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtwkpvyvqw.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtkfnxyeju.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpjliwff.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtxokfivng.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gtgduschmb.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gteyisvrhb.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtykvpguht.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtyjvwsuay.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtgbracqnn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtevmxjiil.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtfmzhkwmy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtebcjgqau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtgwjrfgkw.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtptewxubc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtdwemlaym.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtgcdzbzjs.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtgdesyysg.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtrukkknet.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gttuayvgcj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwduwumfx.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gteswprkvf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtjxavbhkt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrquqkmnm.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtvsuwsyki.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtvexyqhcx.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtgyvrpulz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtbaqwhwlc.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtbltstfsi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtdupafrhu.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtwzeplrwj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtvcxtppwj.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtxkxjjtxy.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtyrfynfmw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtulmzqjir.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtxkhgbfbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtxrrtvpky.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwzlpjxi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtdsflurcr.html


<!-- 参考信息 -->