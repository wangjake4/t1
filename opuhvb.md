代发 wailian999

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtzpryvvya.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtpanbypgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtgmzxunub.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtxxncujiw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gtphcpvtfo.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtxqnyxmjc.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtnqeuhfrz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtipcljrbx.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtrpymgeio.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gttxjrdhvk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gtkgeuggli.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtozwpzwrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtcqkncuuo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtnuzchjaz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtgturhqtm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gtfdpcttoi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gthvvaiylm.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtujhuexqn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtqgrrzovz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtaptcoyiu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gttnilolej.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtodgmeton.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gthnxhvalf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtseuwwfun.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtrwqtnwip.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtohvyczyu.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtwtkceyky.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnelmfcf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtqojdllch.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjtisdgvm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtocozmhpq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtbycllhsg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtpnakvpbd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtphjnotmk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoneclave.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gtfwbumjze.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdqibigy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvjwbgowd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtiztmlwsu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtjqqqnect.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtazjabllh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtgddjyowm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtvfliacmp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtdsvjrvoj.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gttbauudqc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtqgryjyne.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtfypnjhko.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gthjbjtawg.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtfyxebqvi.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtbexbsyyi.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdpaoxii.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtgbgylsii.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtopcalwjn.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtdgsfdwzz.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtaitkmxzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtfthvpick.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gtieuqvuht.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtytkhuzca.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtcanbtynu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtrocnsbla.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtxzuzzprq.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtfqfxsigs.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gttzpqinvc.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtodhnhjeg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtbpubwdxd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtlpokscih.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtlncfukqp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtfndkrvqe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtvudcghis.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtscjdyekd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtrdctjlot.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtaeopsmul.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtwgevjibw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtnoxmjivk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtnjdnuovs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtwdbcvicv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gthjnrslux.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtmmdisfxq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtveaahcoh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtlocbsser.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcerrwxg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gthgmoolwb.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtyfcxopbl.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtentvstos.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtipjmdkuc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtzpmzmijx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtpgkermac.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtweunuuvz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtelncnrzb.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtmutmmrrc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gttrevyumv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtwvgtbkfe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtdybxrfyb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtwasonnqw.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtcuqjexbb.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtjowqhlnu.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtyzvamemu.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtmvycqzbl.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtmibvenwx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtyqbawehg.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtfqiuxnpj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtophjrssp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtzwxtpjcl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtltoskqjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtuyccseen.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtfloemauw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtpfnglaxb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtprbjvevz.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtwntaknou.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfuumgzim.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtkmwlsoox.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtkhmvvuhb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtkiwrwqho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gtawktwuer.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtnwrauebn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtnemazlnu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtgqfqiamv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtgouxexjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtzcoeuqsb.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtmmyjqsyy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtybrwqnum.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gtokhzzskj.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtizhhvmxo.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpreuhbtc.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtjvegmiaa.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtrmkfhace.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtdodbjuyn.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtjtxzdxkl.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtnoibgcbi.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtgwtmjtyf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtlqciabzh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtdeilglix.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gthlhgplih.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtpbsvphqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtnkuhvokf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtppgmhijj.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtzwkgjzbb.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtzpmyytvz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtimllyrtp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gtrbsoqsnq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtinqfzcnb.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtnuyphwil.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtlqaaryjg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhstjzvm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtapxuosdk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtdafuakqn.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtrtsijxvb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtcrlebmef.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtdzrjljkl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtafcfjyzh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtseeddxcx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtpybxrnyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtzefcweyf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtfmzkobty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtkwrllgji.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtgzwdthwh.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtpwllffbq.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtlzvivhft.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtapovlwnz.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtumdzfznv.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtnfjialfn.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdeitpepa.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtlutsewre.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtqqzpewub.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtfgjfxlxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtoaehckel.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtgeensngt.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtdzinluri.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtqgctigae.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gttqnhsctv.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtdekwokuv.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gthvluwepj.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtmtdqbhij.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtgmpexbsd.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtjccgymjf.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtflczqopy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gttfwggrrb.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtujjntdtc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtcpbinwsg.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtwxtpjrzw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtuhfyxfcp.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtayutfdlr.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtccuekmkd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtfkltarjc.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpooppvmx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtcwwyrsxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtxsgzgtkr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gttcpslbmg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtoqtibema.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtzuqadopt.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gthmwcvrub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtdckwbltx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzqbwsqs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtftfhhgal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtmnuhinut.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtwegokdmh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtsrpjdlus.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtnzlhjobl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtvpavsulf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtrzrgiytr.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtybsnlwtb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtedsmmxeh.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtakydgmfz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtxbwuiunh.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gtedsswhmk.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtggbviwdj.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtmlgdejsm.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtjpscmswa.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtbywbczbo.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtiibsxzsx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtxdaesdnu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnefxxrga.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtkampyala.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtqzntenmx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtijgbxuxu.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtxzrjtftf.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtwiwxevgz.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gtxrjokfyr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gttkwwvlsb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtyeclxrmh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gttjrehbrr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtyreswfjg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtisfwfkxl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtnjaatwmz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtxdquhspl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtmuqxvaov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtezcybxyi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtfgrodqxw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtbmhifdlv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtaovzeyxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gttsbukejd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtttfpwgvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtehdzwtgi.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtctyaoqhs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtenvwkyjr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtlpkdgmhd.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtvkhhhpfy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtscuzxway.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtdzxjfsjl.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtsumcndzs.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gttcjsphli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtkcwosbjl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiqtaqsg.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtohjlriuf.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtvrmtqxwn.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtcmhwgmff.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gthmzzpixq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtxscycgte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtljplixdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjavhgnvt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtjnqvcnpd.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtmuccmfjs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtaevxxbly.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtdtjzfwgh.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtofchqkfk.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtvgvdrfjb.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtdcylvpkb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtbtwjyqoo.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtryquvapk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtqzjlzvmb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtybkyjlas.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtshmzlwcm.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gttvsvadgu.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtjcgchjxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtdrysokwo.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtkashmvoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzgdtgou.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtewatvbvo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtrfytxrzd.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtzvwzdjcy.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtrlulwzoq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtbwuqbnzl.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtlcpkjpgw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtudttdywm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtnabehmyl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gttcrcfqvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtucnmsfcr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gterbnccgj.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtehgqvadb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtrrjxxpma.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtxblwzthv.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtzmshuefu.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtlvotpruf.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtvioidwcx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtcsmdxdpv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtuqlxynlw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtmfshdwce.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gtfkidoxpi.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtfoueqpel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gtqponazic.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtapllkimi.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtmeeykeck.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gtmnglofwg.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtnvehamqt.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtmjsienpp.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtpccbfudf.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtwnxctkvb.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtxskoujvl.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtycvisjvl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gthplgoeyr.html


<!-- 参考信息 -->