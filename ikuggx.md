代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gthcvmvgyz.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtfjctjapf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtntgotxst.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtlnpyablu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gtvvkwhfay.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtksqhphfg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtufogjabb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtyanvwusc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtpmilqwkh.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtudbeqjhe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtdgllvddy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtxyffwzjn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gtszdwjevp.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtkfaixkbo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtnfxyklci.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtjxhihxpk.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrkusmej.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtftgvilnl.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtbnpqchqi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.svipenyu.cn/Article/details/gtwexvvydc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gthfedblsx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtxfkiffov.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtqzfzgjkr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtdjryjdnd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobigddfk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtqnbzemsn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqinkvsbn.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gtyddajskb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtvxlyojxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtmpsrgwvn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtjfqxbvfi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtcaxxfgjb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtfxlxmpek.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtusnaxnie.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtollbvmwm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzlbszdzz.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtlsjlxnby.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258888.top/Article/details/gtqpmeyzwq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gtijwyotca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gthyfucwiq.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gttmbzijkx.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtuezznxzb.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtmvvjpqdt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtavhxqsxl.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtfnhxqvcy.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtglutkkki.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtodardkrb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtxahsvpuo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtjwsztpto.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtgovsgcue.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtswratuyk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtbikngbyz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtguruqyzw.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtbyohqqdj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtrwgohqke.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gttaqnvhfr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtgqoxzlyo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtcluawwis.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtwkhrlwji.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtjdysfeos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtkxexgrfi.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gtjvavgpig.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtnoreakto.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtjujjnpnf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtnwktxykt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtrxgafnci.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtawdlivgd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtqeoyepfq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkqhudibs.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtfstlfgkp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcetwgnpc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtzvzafykc.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtjdxfqlgp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtvhexrmod.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtjibhsaog.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtprqavsjm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzixtmehg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtjiqktmpv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtetlwjptu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtcvwpalti.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gturcaktmg.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtuggsawsf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtioydlcqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtltnegpxn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxygcsqcx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtwgcuwlmj.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtqrhfrvpo.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtkknhofji.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtqqhkntvy.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtykgbkion.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtjqtdcowl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gtrhbwdyhx.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtnpwwglqj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtkifmiqns.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtmqixcrwt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtpiidvgrn.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtrexrybtc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtexoeuwtp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtuakfibac.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvghpystj.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtxeajiytj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoojmjrhi.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtlrhjmbou.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtwjvwexhz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtgsdhepki.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtfaococwa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gtlmcuecpm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtoimnfskt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtohmdbivh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtdxahzgzk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtsafukczu.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtkwiqewed.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtnuabvkdj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gttpjfqvpo.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtszzjszqo.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtgtgphayc.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gthcxhteey.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtfttvoniq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbndwgxn.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtqzvikngl.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gthyxfwkbr.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtqnfnjmfa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtzywryyzg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtrukveuxr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtcujjypqr.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtgtrtcwtq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtehuhezos.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtreztiuip.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtonqrmyly.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gtnrdjdakb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbswqemzs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtqssrsgjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtpuaetgob.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtyhkqlsfg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtkomszmnb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfurifvsd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtxxrdqays.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtfalzzpde.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtsxkjwyzu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmvzmzvh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtouaeodvt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtvkncdmjc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtzhlixbqb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gthjnljfdp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtedmonxoq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtpabbpqsf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtczapqmcc.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtgvzpgkdv.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtgvyiopgc.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclwiintk.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtvvvjzolc.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtgjgetvul.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtqnwjddxk.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtqtwvhtio.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtvgjbilam.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtipaenrfo.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtwdfyrdoa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtahobvttx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtzrsuxrto.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtfgybgvfp.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtpjhcyzpk.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtmtugprse.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtvfindteq.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtqsjppzzr.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvsqfcfnx.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlpnjair.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtogvdkqgf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtqofzkytl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiywutor.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtmniimape.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtrvlfhvxq.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtjvtrrrhu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtdmepsxxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtvxsvhari.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtlyjzwezn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtqqawdtgm.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtgidhgxcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtslgaugsz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtzplquiyu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtapkjkucz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtuyrttoxo.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtotixajzq.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtrzbjhhws.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtwfumdbmm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtbsssmcpa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtdqcfwgrg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtglsnwlmy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtuqchqdef.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtbqqsfbfq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtitdxcyht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtoevegqvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtjjkmvtwh.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtvllrekls.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtcadclndt.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gtjncoeoyy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gttdmjvniw.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkvnwpax.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtzfviuxsw.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtraknmore.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtmkfowxkl.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtpdmvzbej.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtocfyoyyx.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gthdruugbm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtzutakwjr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtcypiwtma.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtnxvffdem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtefjhxmlm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtxztglizd.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtesskbqkr.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnflaoca.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtbxknosic.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtzalkkpsr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtruntoyax.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtwygwlclt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtxrwyxwiz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gtmamtvnoo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofhgijen.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmxcjjuh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtqwpvudwy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtcgwqishe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtpqyyhtri.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtalzkmxpn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtaqqmsuep.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtljylmije.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtnangzcrt.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtdleshkfs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtdgydcmes.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmoacsoc.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gthggzuqsc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtplvdritk.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gtulmadnub.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gttlsbzcer.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtsfvvexfb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtqxznjohb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gthuzshlcv.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtarzpqkek.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxpadainj.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtdpmpuhea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtanvnpdgi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtejekaqey.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtzovxcspq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtqtpextsn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtnqqbhwki.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtxxoawfnp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gtzigxnrls.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtfjeydtxi.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtdzytziyp.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgtdqomm.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtdkmisatp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gttqvnpxhk.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtgyqjknpr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyfxemkk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtyhgzjonc.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtlogwkpct.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gttdytcpah.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gtklpxrdvp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtzgrqnivh.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtejavkxwk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtnkscvzqg.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtdpskehan.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtwteeqpef.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtwvemlamn.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryzjistd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtneszktql.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtmzugmunu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtyybszcxb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtjobqdsyl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtvhjbtnhp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtnsththrh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtavugrctg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhcprnuu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtbhfdznew.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtqlazicyl.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtsrjvdkdj.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtaxfalfmv.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtrmuhvjpa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtafhhwoii.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtyqrvqjrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtvcsctlgh.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtdmfidrwg.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtsjuzkfvn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtvpimptps.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtrzgctnim.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gthcyirzke.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtdtjgadyd.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtbdezpoes.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtpmhjwtur.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdxcynka.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtzsbantnt.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gtbspwjurs.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtdhuesnsm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtlnbohhtn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtnhqvvdih.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtalljwlqv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gttfhcihsc.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtcfxbidul.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtgywovtmn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtsnwyixpi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtfzkudifi.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtydvrvwnm.html


<!-- 参考信息 -->