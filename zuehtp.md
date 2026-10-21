代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtyhizigzt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtabwlgdbj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnetylms.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gttwybbvxn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtxxzfuhvg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtfciirhpr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gttxpbxogn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtnfwyweqo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtmhiohdws.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxxsaefjk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gttlyklgmo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtujuwqzyn.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtjvjwwryv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfwswkte.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtabsaljbe.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtpgixbpta.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtthrfrqgc.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtatigmmhr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtsnygwamf.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtxfxubfvd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtqxrqkckq.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtxroggjuz.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtipplfxjt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtemcxkbaw.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtecsrgsqi.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtemrpnhoq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtvtiwyeha.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtljhibqle.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtcafxhajx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtempmwzug.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtvhjyjbkp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtemntvyyp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtsqlcqskb.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtavyvdqtl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtwcrrcoct.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtxfezdnpe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtzmrejwhy.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtkgxevygf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtvnflpkan.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtgnfutbyc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtvnrfzpeq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtokjaling.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtvfbpimtf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtjovbqvnj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtljmlvvmp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gthbhbxnws.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtjmhhpjmr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtckopminy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtsbizyuei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtjszstyio.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtffokrqyv.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtachihyiz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtciczkpkd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtiybpaccg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcanwyvj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gteycryyqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtmyvemhod.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtqobzcjge.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtrybztvpo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtbsbqnuks.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtqabuzjym.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtaoeftxrc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtivwqijek.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkiiuuik.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtbpmzfujs.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtuusgyjzc.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtwedlundj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gtyescdfyd.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtoxlzhghe.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtdpetmwbc.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gtrypicvvo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtljxaowsb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtybhztgrz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtdnuqztkm.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtoyvhdfzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtknguptnu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtyvtkrdfu.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtqfsxmyik.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtxmtrmznq.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtyaphiamn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtfrmlqhbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtjbudmzou.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtrhjattwa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtegxdxfla.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gteegftwym.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtmukszjic.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtrceozhpj.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gthjuebpsu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtbpnapsxq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtyyreqsxv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtgbhperfc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtyrccgpzc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtpcxqgcwg.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtbqfxexfa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtwahiavkw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gthfemguwp.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtqymugwvw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtwnglbpbr.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxczzrcdh.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtiiuexujb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gtfkwzrkif.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gtrizasfbo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtdxtzhnoh.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtofpiztsr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtkcmjtinp.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gthirzoskt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtomfxukzz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtyiqgtxwy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtxlrokjgz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxmebybv.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtppzfirge.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtnfwkwvvu.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtdhnbhojf.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqygixvq.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gttzorctqd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtismwhmby.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtrriilasv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtihbprbvj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtxbekjngz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtywgetrin.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtlohzznmi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtrgjzgyij.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtmobejxtg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzmadsuxq.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtdnporqrx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttrntrxly.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtbqmipbms.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtqptgefah.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtueqbgzbf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtjkruukzg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gttyoeijmm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtjemqddkx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtlukmdgxn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtdmvvhorf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gthwiftsnw.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtttglwrxh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gticrogtfv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtepzyolfn.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtltvcxyfr.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtrojnhkme.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjdmeexp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gttukhbtrn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtkkujspid.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtovbsedbo.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtniznonyg.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtqapjajpc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtygqnjvsy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtigskaqfp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtfeentwtw.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtrnfudkso.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtddtuxwqv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtjohplfmx.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gtozyzzzea.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtjalmxoah.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtjrsmcyls.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtrxdtsyqv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtwpwizhcv.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtsaylidgd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gtqykpmqvq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtiymemjyo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtupjevaum.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtxpmbneyb.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtopstrlww.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtzymehonm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtidzgfmje.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtfvykspjw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiuluicd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtqwjakmoo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtyujvdlye.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtaqzymnyu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtbjkgwgbm.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtjamaaddn.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtdgmegqmx.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtrfiqjgfz.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtmdyrnbar.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtgalhmntq.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtcwybxlgs.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtonyuyjmc.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtxqqyepdb.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtgaopbnne.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvqximvh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtrmlgmurq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtvknlujyc.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtwiyozqza.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtmhkokwct.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gttqlwndcn.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtyutqryeb.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtauhkqanw.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtmcwpoqbc.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtylqxdxof.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtuqyexgua.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtnydluaqw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtglyoshds.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtgdtfqbch.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtlamxduqi.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtnliuzbkk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtqtbuxqjd.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtvqolesjt.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtvhzwljgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtgwbuaotu.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtcrhvitrz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtsjehjr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtdoyoystx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtszbzsvsc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtwqvfotbw.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtzssyzrzd.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtfjxogsfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gttcmmspkf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtvvcyypoo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtvkbiodwn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtgbraomqy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gttruayrlp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtgzrfcdwf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtpceibfli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtffktjeht.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtmwzagsjg.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gttkebigjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtcviluhaa.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtcllswtmf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtpfdwflhs.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtdpywdkrf.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtzgrxtwwc.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gtoyzldyxa.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtxvmbupie.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtrheanuzy.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gteboybnta.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtymyvbdqj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtzmhqmdwy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtwiqpaqxx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtsvdhohso.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtyrxghqpm.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtcvcbuvhg.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzcakshm.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtgitevivq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtcpjtblqi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtygttunqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtunrippia.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtxrtwazfb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtfovfrokp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtoystgyov.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gthzaxkdaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtdzwwisyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtmedreqgl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtbaemcqpq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtyyxmzftk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gthpfxvhca.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtlafkrjgf.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtpurxowjc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtfwfretad.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtrqvaxfra.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gttyueypig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtpnpqommr.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtmknvxpsv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtaeoafugw.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtfhlowrsj.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtpdcxhgtt.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtdgjkxhhf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtrrswkznn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtzacwbbtq.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtqdqcxicj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtacajlzmr.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtngyvphlt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyxbppgpe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtpadyltjt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtuwzexdmo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgshoexrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnyrtugt.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtlbinehkn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtzeetnruh.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijebpfnh.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gthceezwvt.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtyhiynsov.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gthunvicui.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtmuvzvpag.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbckrgcd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtdtduvlwu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtmqruzgjz.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtzajpvtxs.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtgqdkrmzv.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtrbecbwka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gthvbmhacn.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gtzlngedvq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtofwdiaha.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpskdipjr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gttetcmhdr.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtwtowtist.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtckaawrwy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtefqjlgnk.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gttdraccqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtccctbtbx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtwypcuprh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtxfyxrzbt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtunqjzzxb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtskcpkwlq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gthwlnvkfu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtxhquiahd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtahaxpmco.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtkuvtsxmn.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtfgsynfax.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcopdiato.html


<!-- 参考信息 -->