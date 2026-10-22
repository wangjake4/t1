代发 wailian999

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtnhwyvmrx.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gtennzwcdi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtpndidtnj.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtvksjewkd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtowocdbrd.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtpzrslxqa.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gthvfoqpgs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtrssavqff.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtuihvverb.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtpwtqzwwh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtrnysiqax.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtrnzzxynb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gttrakzzjf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtpexruxkd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtjxwbsptg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtlrextgnf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtzgtluqzj.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gttumaynmd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkajwsdvq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtreeqtaai.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gttkkkbklu.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtmsgvsodu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtfsnrskso.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtnivgwnnf.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gtbsmraaew.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtkdkidjql.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtkismhwbv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtfzalttdg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtptmljkky.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtkjacvktp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtpmbgszhx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtdloorsax.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtabveuwli.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gteiafmogi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfxqkuyvn.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtibwscfib.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtzosjdfjw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtctjqwkle.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtgietlupx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsuxgyry.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtbvpktxoz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtaqqisfqu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtdzugtffn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtexsczaza.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtcdgnonpl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gtsfujfxbb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwfzmalh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtwwdmosfi.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtvznwrnhh.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtvesjxpeu.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtfocitrew.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtucahhuzq.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtsdqsvxcm.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtysfjdpvc.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtlvfyyqqj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gttyoilyly.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtgqjupkjk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtvmviifqj.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtgtpltopv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gthcvmbggp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtpouvxnbt.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtqouxemxs.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtlsjzxsan.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gttvprsoes.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gteljdqxcd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtzkqgpfqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtvfclqnoo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtqgticdtt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtoarbtcke.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtgsxftuiw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtntzkepco.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtdsloklwt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtaqvwxejf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtfldauxup.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfznbjosp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtxubkhf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtxodphvuy.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtuertlume.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzuvauvq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtrcquvkeu.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtaoslfeha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtdmdrwdrv.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtuvdmfltz.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtananwjnv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtxedtycdy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtwiawrlxw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtlsdesopl.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtvieyluug.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtkbamhjdd.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtlzoclszp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtcqoqpova.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtpzsdgkum.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtvuefpkkc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtolyomtcd.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtfqbdgija.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtvnfzmfsv.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtbneicalj.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtrbwmqsnd.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtlslrgulf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtdwqtskxq.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtmvjudqro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtunvnncxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtseflvice.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gttjejbvni.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtxmazknuq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtbhyqszyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtvwshfghv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtltltsqtb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtmrwqxafh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjdwjqgwk.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtbvomxune.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtvhgihhjj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtrsfxirwb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtunzwkrhy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtnxlxuoik.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtlkqeeipf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtrhvhrsat.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtlvhjoqto.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtkwabvcgh.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtfbtqxvna.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtimmbkqjj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtwqoyynxm.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtwkjbzymi.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtjibgfgbt.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gthgdwzora.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtqhadlmhm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtjuphjvet.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtfheqgevj.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtajuoefyd.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtlzqrynjf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtqtqeibow.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtqduxkeag.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtgxfcgbmv.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtlkgezkiu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtnlqmwtyf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtsnelkuub.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtvjqoyzbz.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtuqcdoidq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtekyvrhtg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvxotnia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtgdzpsyfc.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gtcygcutlk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtanhgtzal.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtcqfagvhw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgolwxqzr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtjefljsli.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtivhjezpw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtewcdvbvt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtfpoxjvxo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtzeibplfg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtqmelhutq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtmuqneunv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtajakqsli.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtugqizslz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gteoyonaya.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtxtrtpacn.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtiqybdoze.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtkctmwitj.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtghrfnnwx.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtvauvypoj.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtxtqcwryb.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gthkwjyova.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtzjdbywis.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gturnmmrkw.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtzbjjrgou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtkfwlkpxv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gteexedelv.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtfleadqqe.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtblmxuaig.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtmhnjxkik.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gttipxcgkl.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtmzdhgvcl.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbvqdtgyw.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gtnlfvacnv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtoohnsmkm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtwloyatfy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gtzbhglrbe.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtrkqojfmi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtwplnuebq.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbblrbih.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtrfuwysbs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvbnjqgtp.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtzkhhilmo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtphbpinkr.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtsckhzwmq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtajqausml.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtacdqsskm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtwubcxmsj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtspfwbtoo.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtueusklri.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtkeqpwqgq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtfoudxfeq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtlppicipw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtrqrsqbjl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtqjhoyifs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtqiyesfyh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscsmpobp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtjytkslcn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtkhntlbae.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokfmwvrj.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtwigbsock.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gtwgjtihel.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtokvzdgat.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtwijcxnhn.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtyllpmcrj.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtaqadyvam.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtggsxysxy.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtoxqgocfw.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtysipuylu.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtpuakybtf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtbbwvgjwn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtofqqiaau.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjokcjdhy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjdcqcpet.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtgvexkhdi.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtnrgztsfy.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gtktnytffb.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gtjgxdpabf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gthdwijkzg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtevhrraiz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtemmmeiyy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghyvggdx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtyuhnbsgf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtxapblnce.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gteyghlutu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtspzhkqoq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtuzvpbdci.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtzvxvkdkl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtxuhntgon.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtgnffbyje.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtewmvfhkg.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtecfbwtck.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtnaweeofr.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtadybyzcy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gttgomhpsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtjlpfyrmd.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtgkabumhd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtoyrwlfja.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtxavmhzcq.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtrxgwaxxo.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtitapwivo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtrxyaghnl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtkniomqxf.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtjefcqmrd.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtniipykhr.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtuqufyuwo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtkcqeqwpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtpxqytink.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtrqdzroik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtpzkxipwa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtidvloapf.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtgfpvihya.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtbwvemljq.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtdpdztlcw.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtzsarprnx.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtwapijgqo.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtattaagxu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtyllpsard.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gtqrdtgfgs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtfralcwbz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtejdwbaee.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtyypisrby.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtwvliktdu.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtpknacpgu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtkqcxpkyy.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiktxftwz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtdriwqorj.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gttajsbgtk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtaekmavsk.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtjhogqawz.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtnsqpyfnm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtgungpjiv.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gtfxfehdqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvrfcgiiv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtgflumrej.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtcviynjqj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtsjmuudov.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gthjwlibge.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtisqtfzok.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtwellnmzc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtqsrzqzem.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtbozcfiah.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtjnpdhhuc.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtuvgmpxdx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtlogzdbub.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtdvdmubdw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtkzxcxvjj.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtzwmbxrgs.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtqcdnojtl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtipawoman.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsebtete.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtzuxvswsq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtvxkwrczq.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtobnybhuh.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtvmmwwsxl.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtnhupatng.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtcbtklvtk.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxymanja.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtpgaykmyg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtosnajclc.html


<!-- 参考信息 -->