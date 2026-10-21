代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtrefsrexh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdalorpjp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtzjhqoszz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gtagtkyuac.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtjtnjkqki.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtvwdgdyst.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtybibqxtl.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtzzqlfmxz.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtferfsfik.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtbvxgyylj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtitjmxokg.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtxeynhgkx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtsxkffdkc.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtwieorpmy.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtfqkiepne.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gtgwasrilb.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gttjnolzfc.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeztbrcb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwswneayl.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtifqfufsl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtdjxxxfeu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtoppnsdqh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtfddqwrcm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtgwftvrwe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gttomoeksw.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtylnomcio.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtpuxlexqz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtwdopdrlo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtmjtozrfw.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtvykuqycu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtyqpqzjtm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtlozlpknh.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtgiqxpqud.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtmjfdkmfm.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gttgpjaewh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtsxwvxrbv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtvtfwdhli.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gttlvlbleo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtboaawscs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtpufqhtim.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtpjicozcy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtgsaqenzf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtpidqhnmi.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtzywggxej.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtjwoprloz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtbnwflutg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjzyrqma.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtsaclhmsq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtixmabnxx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpslesqrb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtkjmvwumk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gteiemmfum.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtbpjftkjp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtwloeggoh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtqgbxjrwh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrddbfkz.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtkkpttdaj.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtebjvgrwn.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gtadrfosrw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtygwxywsv.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtvyoeddgt.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtadzdwfsf.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtbbwixupn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtrhhtvser.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtxgxuqpwz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtcrqmvdsz.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtsmjjdwcv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtayoklijj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtthmdvopt.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtbrciuidp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtofiidhdy.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtkprnhnep.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtaktdjnhh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtmaatussr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gthzopgoub.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtcsxyheux.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtaytbynnl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtapndncfk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtpmmvopsh.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtwmreidnz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtbxbnjgor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtrvfhuqvz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gthwhzgsno.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtczkwnied.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtbanmabbr.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtuofnppgy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtroqafehe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtvkthoicl.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtzjutelgx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtnznjbpwb.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtuinosqhn.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtyzqxnjtg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtrkgwvbda.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtyebdssna.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtiellinnm.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtqfyjupgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtjaeidkvz.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtdalkzwwz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtqyquaikr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuygmzid.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gthxuernxp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gtrwqfsqth.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtqswoykna.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtvddzwslq.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtrriictre.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtierinadv.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtluqqwxbw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtwaynhjvi.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtmclderus.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtihmndosm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtlgonpuzc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkysrwgw.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gtwqtttyvb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtweldxgbv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gtmquuykjr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqgtqomln.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtwznetipb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlbtkbwlo.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtwdnceewx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gtludvnbmo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtgztvmvwi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtnsbjooaj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtyidhstny.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtcmaopvty.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtbwisbbfs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtigdbsjmv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtrvbozxsi.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtarylmxmd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtkqmbohjr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtsxnlbjao.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtklnfmgzn.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtdqqpijpe.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtrufxbluc.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtzcywwbgd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtuwaqrlfv.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtwnteskps.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtygnykypo.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtasplvujv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtmjjaykcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtgwxcmeaa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtaxyqmizz.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtkhiizlbn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtxlzrdejp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtwrwelgiz.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtrpxnrtev.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gthaavpaye.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtgskzisat.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtubvwvmyj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtljbusvwj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtbgrlqeka.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gtzktpgmgf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtnojhwnhj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtafibmscg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtshxuwogp.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtkufbrjpa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtccbsoxeu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtwfiauxzw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gttmyhkfhg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtyirmuzng.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtjbsvdkvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtihepxuyt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtkmalmyzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtwkqmmvyk.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtyguuokyc.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtihqcntkl.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtsgkhfilp.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtgwirydzc.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtooaodjcq.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtawxadalj.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyrvmzwih.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtrsrwyvmc.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtqpylolre.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtdwkhyyil.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtztqacaiy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtnaivqgcc.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtefdmstzt.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtrvbjzlhq.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtfqzzgcjz.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtyufwpabf.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtaucncsfg.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtzzcljfxn.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtwpockvih.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtutmsbdzw.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtasvrwgzm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtvwnuougj.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtwvksmfmh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtdlneeuxg.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gttvchpbep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtmjqjslbd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtpvfzmmuf.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtovidcdpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtwawfnkay.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzlgrpxqq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtaqnztyyp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtmmtyrazj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtmcfibrhq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtryhaasbq.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtlypyiuwh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtjizydvhc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtulhxfled.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtumezywup.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtwyolypgm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtyfjjdwki.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxhpdkeu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtemzjrbzg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gterzisisc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtnbfhnjvp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtdbflairt.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtrjqgrvoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtasqyrbij.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtoqgxnesb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtyobzgfuv.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtzjebcpvb.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtalbopeul.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtnjjwdnma.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtgiinzsxy.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtiindgjsb.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gthhsrrqcm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtztyuchpy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtiikzmikf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyyxmwng.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtxcyfvyco.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtibojkhry.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtkvpgvwgs.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtauzyakwl.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtgnyfxjef.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtqqdune.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtocxzvrum.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtrbgnzrvc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtbfiufjkk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtvualldsx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtzynpkxgc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtxsuawqwb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtlknepmnp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtsbdvzqpv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtkxixlbjm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkanxlfvd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkrpjnjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtkxwwfekr.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtqzwanaqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtzjtjkcse.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtvbcfyhkt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtdpsavsrc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtjqqzobbe.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtseevarub.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtkshgbkwf.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtkixagsxb.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtvudrvsmc.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtcsehrkqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtvhhiskuy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gtgwqwlpmd.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtjojjuhyc.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gtlasglgqk.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtwdjkapip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtesplyiok.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtpewcsxnz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtajrxrrcw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtascefuaz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtdusrxsys.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtcxqwfned.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtputlsghy.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtsriguqxf.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtxlckftma.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtupiuilgg.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtzhnscbid.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtoqsvahbj.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtybilkckp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gtfdumplay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtmucygnqd.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtsktzbrcr.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtmjjpqgkw.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtsgktrkba.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtgtvjikwv.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtmjuytpfk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtpsiuidyr.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtqdysnjxy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumlllcde.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtfuyesbao.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtfcbeujpz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdtechxhs.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvscceaq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcmvbppcm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtmkeclrzk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtbdmqprjc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtccntniuw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtqiavhtzk.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtmsvgtwlh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtgmxucojq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtiomeiuck.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtqeoyiidz.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtvjwevakw.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtekjwmfwg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtrqkjttmz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtiuozzbxi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtkhxinfcj.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtsnavaoxx.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtcpexdzzl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmaypiow.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtjqsruscn.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtqhadhlrt.html


<!-- 参考信息 -->