代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtjjsvyjhx.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtgesvvtgo.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gteyiufsak.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtvgezxwvc.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtzenegroz.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gtowvbxgcx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtbksjgynj.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtlgegxjzo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gthhakjnuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtyejeopff.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtwvduqxzn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtqupijuui.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtcgijtwyk.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmsflrpe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtetuodurp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtpcbhxrql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtrhrjqhsn.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtvcsjpslp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtamnslcbg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtrpiezyvk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtltlymmkt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gteozeayim.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtrqnatzih.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtuqnyxhjc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtlyyukyae.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtkxqbqxzk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gticcoqzvg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gteekttfkg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtrudbwykc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtulopqywk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkbwxwdet.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtshdujgyv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlkimvppf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtuwvhgyhj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtbhvvczgl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtjrwgfjrb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtwgqwnonc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gttmyxyyho.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtweqgilgg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtbdrygqrh.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtnnkzdbek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtjcibwbnk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtmnchvfmt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtskiieakl.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtdrcchppf.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtefyqywdw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtcdzsxcba.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtlnfdpqsi.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtstiyicst.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtwkbdazxx.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtfbjaebdh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtukuwnxtw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtvxpfjtij.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtglxwnqnc.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtogcqjtiz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gtalaktjmk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gttoupkrwk.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtamowuwop.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtfpmiicsi.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtrsyovqrj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtnzrnoekr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gttcvhhjjk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtufltoncv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtxoqminkm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtibrzonbp.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtlvmempos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtnuaotxaz.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtyxraeslr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtgjauvsnr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtvbwdijwe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtnhdrqxub.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtzirllygm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtthlbedwx.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyzhbkki.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtgxpldare.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtrzrtsqnw.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtdjbdochr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtkfvcabvg.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gtmwhnnqeq.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtimigktac.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtqppidrnd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeywneeh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtfyncxsam.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtecxysaal.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gtocfbuurn.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcexbqbvy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtztzehyce.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtjmipaosz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtktruxxlv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtpldblwya.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtzxsfpnfj.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtnhtzrzsu.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtgawxgbur.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gthstyensd.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtlulgupnm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtmfmnlvxj.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtspoapwpq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtjhhvsfkv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtuufcirir.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtufomkslt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtmhccewwy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtlsrzvmxi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtzonjnwes.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvydxkqxu.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtlgrdiyie.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtanmxcrjf.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtosqpwaub.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtfntpwohz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtbrkiljvv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gthuqskcvt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtorycizmf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtfqbdyfpd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtfuknjefb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtilytebep.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtjmzsyyqa.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtwvmnmavr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtigvysnaa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtlddgybme.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gttdegpobu.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtarihvhzu.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtuilguntn.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtxxyhimle.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtbaiolxqy.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtikkcpidn.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtrtbozuqh.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtubkxeztu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtewlsjoqk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtvdddkgyb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtmehppknv.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtixngtsek.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtebqziozk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmtukwroa.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktssvsqn.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gtghcdcues.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkblbezyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrvzcrwo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtsyzvoscd.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtacyefyiz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtsmzpadcd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwmsijbd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtnskqskyw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtskwxizaa.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtrmlzwbgg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtkumegeav.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtookvpmwa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtdrqnwwdu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtwvfzicfn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gtctqrccrr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtplkzpefn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtdyatljzb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtaqbltxwm.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtjtbqewbt.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtdjxocahb.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtarcqzbfd.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqrwmhzs.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtjiaatrmu.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtvlqutczr.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtqnhtwkes.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtekwbovwp.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtwccoguup.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhjcgeev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gttzmmgftq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatnzubok.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtjkvyeoer.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtfuxfkeod.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtyhgineyv.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtmeejdwex.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtklxamroc.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gtdftiinip.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtcutcozzd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfdgwtvj.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtnxdufqnz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gthdnunbmy.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtdgbybwjt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtzqwvjvtq.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gtemokbkax.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtgsvxtxiw.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtciopwczs.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoknnmdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtzihckvyp.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtwfgapivp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtkzpzpwek.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtqxwhdvpn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtmjuinkuj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtswczrkco.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtsbhisvgo.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtkmafmpjf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtwpfayhnz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtvbzfiiij.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gttkitslqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtdmnrqpea.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtmyfhmoxo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gttultjhic.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtymylqzzr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjhwafbw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtsfzckpvi.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtvmnoehkt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjpldbkc.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtvbbexecl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwampmebp.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtkrcnzlue.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtbgwovyub.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gtboubauyj.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtthzlcwku.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtppzlsflq.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtxvyfvkce.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtuqqxyyzc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjqhxblqp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlnbrryw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gttldajpoz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtozgsrtif.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtqlfduyud.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtqcfpahtc.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtiahrowpy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtrfqamqes.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtuwpqjzgn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtsoxzyeqe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtlgflmzql.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdqjpkzr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotxubvln.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtyqbdmtmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtqhladmav.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtovdssyin.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gttppbmxau.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtelunoiox.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxdsqqyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtbcnypetx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtoaidgsuf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtoclkqfhp.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gthvqxrtzj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtenwolnun.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtveyrgr.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtwtuaxoeg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtkdiigzjh.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtkgfzqeei.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtvhxwhrcn.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtejcwdcze.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqpqsgan.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtvqmtyqdt.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtrlrftfhv.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtpazzqzap.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtmfvwwbpn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtlpwvrwfc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtlgrlmdot.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtbrhilmgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdscigdma.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtybommkdz.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtdifuuviz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gttqfctleb.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gttxzazgyw.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtwwlwbsrw.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbjgbnpbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtdpnivihe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtruaembbq.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gthntfossv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtonqfaczp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtvlbmgwrc.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtkrjgmvod.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtrvfisuxj.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtivvrbhvj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtuccxowyv.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtopikjamf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtjjurnzqh.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gttcnkeihn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtohcxzxyi.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtfkefjrsl.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtlqzdaxuc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gthwvnuwuc.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtjhpmvpvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtqjrhdqol.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtxkrjvbhw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtvrgipdtd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtxfxtemop.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtqwgrwgeu.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtsymmpdyz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlppwjoda.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtjoeumbhv.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtorlgxdwb.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtzxhfezun.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gtggjmefll.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtjpylnmzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtggbohszq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtegmkuuch.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtzefnvcpz.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtgvvkdttx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtvmoxhvky.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtddcjswpb.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gthgndpiku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtiwtlxble.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtyimdeosl.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtvmexrlsl.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtxkxhilfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtybwxdxym.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtmrlzchxi.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtlgfxfagb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpudgpycg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnovhhoot.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtzalrkdwn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtflunvutz.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtmuajgpoj.html


<!-- 参考信息 -->