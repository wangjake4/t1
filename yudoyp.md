代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtbwwfiftw.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtgahpdxpn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtufbuuksb.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkspvzgd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtdtthztjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtzztgwucq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtsipyatju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtqkxupoow.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtaphunjcs.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtuualhqem.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gteskabhyt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsikljhfa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gtajyfqucl.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtcabfothm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnmuycfgm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gtnlnzqjjd.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gttitxkxuv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtzaoijitm.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtlqtjzasx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtdrefuiph.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtrkcfsnkn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtvieeqxvr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtahxqmrrq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gtilxnlsrj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gtqdhnfipq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtdisddczd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoixssde.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gthxnxwkki.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzqtkapq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtwhnumfvg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtejegnhiw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtiwuwmsvp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtrsokwzvb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gttxjlcbpn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gthchdbqtu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gttptzrjjw.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtaohmdnzx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtzerzezfn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtfyksdkyx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtlaxyfijz.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtxdwzjwjn.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtckcoucly.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtqbehloxk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gtwbsvljxd.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtgmjkoedr.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtpwcskdir.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtdqykygim.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtlwovbhmm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtbwpauwzl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtujezvouv.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtepbupswa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtzoxlcxwj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gttyvbnmjx.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gtqaclcjfc.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtscfjgpvj.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtwbcxunwm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtydchatlj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtrsfjlkos.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtijnpziti.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtqniljikf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtqoicmonq.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtujjbxxve.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtyswvzere.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtrwrunfcj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjhoxeys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtjoqshfwy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtjmarszym.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttxbwgcig.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobrysgol.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtusovqogh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtkpvzaxpu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtgaanfvnu.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtmwixbioy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gtxlqepphu.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtouzthjyc.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtdrnvgthi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtezqimggd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtcezecboh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtxruffukp.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtguisfawl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtptxckgpp.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtblcubuab.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbxemijn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtifrjlhxc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtllibttid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtfzjuxwnw.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gthbukefdr.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtziwzcvls.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqejzfytw.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gttmekuihe.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtvodcctrt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtuwtopmlx.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtlhselghg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtserloonh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtleumdeqt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtrctrfuff.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gttgpknovf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtwrgwrfls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtdaaqxxcq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwfjcxok.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gtcmlkvwyk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlumqozhi.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtsyfzembk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtxhgoiscw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtehvlnixf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtuiupaqkt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtcppuvixj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtnqcfuies.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gtwbrjhvhp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtlgtkhcmk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtsooyrzzt.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gtudoxwgnw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtlsizknuw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtfwudsqbv.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtoraanrei.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtkxfxabqu.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluyhwrxf.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdnothjm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtyknvwffe.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtrwmyumwf.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtfitnynub.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtqdhhjnkj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtfzerejjt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtcpyfeyjs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtppfgchsb.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtiuixnqjc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtomuwerrr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtpzrfjhyo.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtnnucnmpq.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtbmaofpqe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtoforwj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtqryzpmsn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtizssviip.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtlflrzecr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtwyodkukx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtewdcqpyk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gttnwfwvjo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtkiwgtznp.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtkkvlvaba.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtdcexdwqm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtdijdceoh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcobbcst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtwnqohaat.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtwbzbnywx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtfkigcnru.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtfzsdwvun.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtrucaosan.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtpxzkuswp.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtzsjrkecm.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfacieyse.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtwnvplpkn.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtqszdblsk.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gthdmzblsn.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmosdqyv.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtwtatqpcy.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqfzpadc.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlyxdscm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtiyylaskl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtraduernk.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtstynmnko.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtnbazggqn.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtehvdmall.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtryhghjid.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtmtfleaaa.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtyuzgdztl.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtxafteofb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtgzoriqjj.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtmknahxer.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtwcjmoljo.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggxrfetj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtozipoulz.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtciwzqqxf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtwerpehoz.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtsvwxhssk.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtpgepvfcm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtompovlun.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtuffctksy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtvleoygyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtdkgyiorg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiwhfkei.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtlzdvalua.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtbdvimyju.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtuheulwvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtswtyigdq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtyrycsxyw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtinxvxrxf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtemjvzizl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtebgezxpj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtlafijzey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtdxkfhggd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gthpvoxvnn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtasxrjker.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtiodijemt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtdqqlbjsh.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmrzyedln.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtihvxgysz.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtwncwjonk.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtwjbkreql.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gttiwtvroz.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtbbwiegxg.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtzdjkbtfz.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gthfanmznf.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtrvstnvqs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gttjdoyujv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtxrhrrerl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtdocbdang.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgjpsgwc.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfdxwjrs.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtqarzdfec.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtfefkjmyg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtsruztxvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtjiniksoy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtqjnhnfts.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtzkdxoyoa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtxjivfhqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtuvromiak.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gtdkfvjrgr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdgspwkt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtwyabosqx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtlkupqjyf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtoqqklyqu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspmupdbw.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtmypwscgw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtxkhkwgtx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtgevjhyxz.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtqqlwdolt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtlgsygykh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gttviwhtdc.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtefenvtce.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtyqshlpbs.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtftquujyl.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtcbvxcboa.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtglwovcxe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtzgidmksq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtpnbhpoeo.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gthcfomkst.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtlxsxserv.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtbfllpzfa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbarvvwj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gtsjxjazvc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtymtqvqdw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtuvssomzy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtvxgaszvh.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtghmwojfo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtisoqxssl.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtbnhxrgwr.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtqrhfhewy.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyuwjjfj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtjdygvwga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtbrnhdxqn.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxluldrkc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtzlmnalgg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtoujsedin.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtyegzhqio.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtgbrlphae.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtepddnu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtsoldjrrx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtnnwitxqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gttbgxaxbb.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtzppioyfk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtskgjbhga.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtyduixlig.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtuitfwjyq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtwomvchvt.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtjlgyeyxq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gteoxqsbvz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gthesnxyge.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gthdxgoyci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtnqrwkxdz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtvhqckwij.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtbvgztjku.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtkwpzktyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtevhrgtmp.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtycwmmsar.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gtpppfzviv.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtetipciem.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtmecxumpl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxhzinmn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtirypmuml.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtxqgrdcah.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtwjccdoqs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtdhsliydf.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtuahpyyvc.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtepgrmvhp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtpohahxca.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrfaolmz.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtqghnuieo.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtusoodrau.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmmmvlmt.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtbehpvofj.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtwzeslssz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtuzrcyuhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtzjwmmmsr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtdvdamytu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtaolbqldd.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtaeexrult.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gtrvorbeto.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gttsnejezc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gtkzfiscki.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gtslibomql.html


<!-- 参考信息 -->