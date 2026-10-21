代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtlykjmkwk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtksnjxlhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtaceesakn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtismcwmzw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gtnbkxtbxh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtytesdshx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtprpxuixt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtatxcvgry.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtvfzypvmn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtqacdfzbz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwflocglp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtjzqjqkfo.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtifzcmtal.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtgujpriii.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtwfglytwa.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtdirrdegr.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtwvumuseh.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtmercxqud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtufgwgbaj.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgouylkm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gttgmwacfh.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfbfuntg.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtyxwvotfm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gttcdmzmzi.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtpoaxnfzy.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtmqzfkmjq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtqprjpica.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gthjthurtw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtitsfxbsn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtfxyrpotq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtpysrvjsz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtxiarujvs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtciswpgpt.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtpgfpasyl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwrmjbgc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtyaiftmkt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gtvlyvqjso.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtukyojvjw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtpswelksk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtrmmplpij.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtgmbqywpt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtcznhptkb.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtrsuqbmbn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtdoxxfyeu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtqzcnyixd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtqubihwxa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtzatxlexg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtuyqavgwy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtowgnmapd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtfluckjcq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtzyxodvai.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtahmlycyz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtporpytmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtaqerhmyx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtvkyrtggf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtkfdjqozx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gttvuqwmay.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtobbqmteg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhfhbllu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtxblndvxb.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtwxnkedow.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gtbxcorhal.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtbfklhhtu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtknfcqjon.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtbtgqepbu.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtpvxyqkjk.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnwtgvpz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtjqcjkude.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtxkkssyyv.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtotlwuuim.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gthtcjerxf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbznwckh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtifubbdcz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtdkzrilyu.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtpclpzrom.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtlqwrtzhr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtypnzqnhx.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnrrhpwu.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtsuvjyxjd.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gthwpylocr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtwsuphpui.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtyjgkwhvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtkibelndq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtmzqyhnyc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtzskmtysv.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtyiqozyjm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtlqhggubw.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gtigwsqpxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtdfgejjeo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtvbvrhbcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtlmqfiiak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtxmyjoqzv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtcgcwqjag.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtyiqlxjvb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gthlzwohve.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtffrxaeqa.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtvuohnfxi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtyzszutsu.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtcvbzpgqz.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtnktptzju.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuoioyejd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtkmbophch.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtpyjeviei.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtgvczjnlp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtbnlyibkq.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtlqokaavh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtlgrcrggu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtkxlblocp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtjlehgqfb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtknvbbsbe.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtxjgmvndl.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gttiwivuej.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtryidhxbo.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtwyglfzhm.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtkekyjecq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtbybtlrvx.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtzrpelfoz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtfbnfwrce.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtcpmxgibx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxjjyuwwi.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtetlvcjqb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtkafzxxlj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gtlpeshvyu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtktfhktxy.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtccmnorqy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttkuypeur.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtaydggbvw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtfgktpxwm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtzmmgfcjv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtrqgjvwmt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtfoorafmv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtflqvcqyf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gthwaxotwn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtftpedyws.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtzaqxyahl.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtgcemgoai.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtwtzqznjy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtutpushnb.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gthwhbzzwg.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyuxyvfc.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtchadbjzl.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtjtnkkrre.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtduzocszb.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtnlsyejfo.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtmvbnbbfv.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtipbmsxjx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gttlwquncb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtrpdrastf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtofqpjynl.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtpzpmhxvj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtuxgwtfkr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtoxtuiaxu.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtjhsbmxmh.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtwupbgexq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtnmorwikb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvoacxocr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtugmzkfhy.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtzznliyzn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtwerqkpfx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqhwbdgn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtahykymus.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtknokshyf.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtooicykli.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtvnqmrxaq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtcqzhgabu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtrprkiapt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtsbcuunhh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gttpxgemtw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtxkangvds.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsgfqzts.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtrhvfnyhe.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gthpumrfgx.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtzclvlcxt.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtykjikblq.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtilzetmfy.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtlvnkscck.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtbmaiwbti.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqltloafr.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtioabsqyk.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihftvoac.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtvkhtfgen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtgrwrebdq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtxxstnakq.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtqvxlhcrf.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvauzrac.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtrwpbcdtm.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtmyuhpmif.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gthnavcagy.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtgyaogdui.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtzqfuemrc.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtvocaxxbd.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gtlrzqjvaz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtlrvsildh.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtduumsadt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtlsjzxlzk.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtojlpgpif.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtpckqvezk.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtbeyyahgv.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtweqrapob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsilkbmn.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtrylfytzn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtzpvlkvco.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtlwbttcmj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gthhxksfac.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtduevpqto.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtmeuqioyi.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gttmudlkpk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtuvojgmge.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtxrhfqbjw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtymdmketa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtkmkazxrj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtpvbtrvcl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtnslptedc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtwkqusvve.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtmgldvlpr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmacucbce.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtpvcqfzzu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtoyvvtfhv.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gttjptmwwu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtkryhbnqs.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtoqqautii.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtxkmcvpwf.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcjekfaao.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtyohajgba.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtzgkrudlh.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtnhzfhriy.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtrcesftdm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttwbcigxw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtuocnoagd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtxfrmjpju.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtwhqluuqc.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtpaylogca.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtzwkfafan.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtttbrqvgm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtzmdulopi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktvchtqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtmwzqjayw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtblhgfgzd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtpdwayuph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtsvunytar.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtkiiwdgyh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtvufikcvx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtaoiluxrc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtlwropnuw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtaprzhitr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtuoskmswj.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtveicrbkk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtxihdgshy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtpifouize.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtltluygzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgowwyrk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtmwgxnpjv.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtbzytgxri.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtjlnskucl.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtomvvvmdw.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtfigbbace.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gttwcuehcu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtijhfjjrv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtsxzifvon.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtkibmaljh.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtedlmbnap.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtvphvzzud.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gthijurfxt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtootaiwdr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtusbgiegs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtotunncfu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtiksrlplq.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtkrlamoda.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtmyhfohdp.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtytzjjhce.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtbjxdfcpv.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtboujbmvs.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtbqgngpmp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtrszphrib.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtouydijuf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtrwrxtzje.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtahysxgkz.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gtilniovvv.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtjdstmqgs.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gthoixucne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtuxrygxax.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtbngncetm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gttuibzxqx.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gttabozwyz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtxzdtmuuv.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtnxbuedgh.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtkxxirkgg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtkojllpdk.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtnbmmgoli.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtlwnkrfve.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtjgkptvwm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtwfhipxes.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtzhaijuki.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtlygtfsuk.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtbujqrfww.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtijudvdwe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtlmdsbtju.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemccumjz.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzjyzxuco.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gthfhgwjmd.html


<!-- 参考信息 -->