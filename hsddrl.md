代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtzdcgthqm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtpvrlxvwn.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdtzykelf.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxdongaq.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtpllsmyui.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtzimibyuu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gthccixukh.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtohnhiqul.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtycqzzxgy.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwxkojrb.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtvbknefcb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtcgjuqidp.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtdwwmzefx.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gthroenosp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtsbzpwnzk.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gthyxeuafu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtqjjeulnd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtmntocxuz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtybjvggvu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtkvkphrov.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtndhwcusg.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdxeqxyo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuanzhike.top/Article/details/gttcqgkifr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkxubkqby.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtixpvaock.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtmpwivhch.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gtfbmcomzj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtbejumzdb.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtbbmagxkh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwucpguc.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtzgnborqm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gteleqvoil.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gtirdwejvh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtlxbjzcrk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gturietqen.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtmpzxdzdf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtfipmfogt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtfdcvvvkv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtklonbjap.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtvmtwhilw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gteyelopag.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtkypsitmx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtnbiqnmoh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtyaddqdso.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtkmwfvkcp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtalexrakf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtumysohyn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtyujgedok.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtbgkoytxy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtszhpiejl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtwpzdygog.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtnjknusbq.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtpdmvjpyw.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtdmeajbcu.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkomhakzp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtbedgauok.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtovjtwkkr.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtrxeddjdo.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtnqgeibvq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtvoppsknb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtpmmodhlw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gthpciqwdh.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtgdyvubzc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtcvetddmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtjjjilquv.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtiuzopucr.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtuvoqojqd.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtureythur.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gttlofowkm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtbsyaezae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtqkxlujru.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gtvpwzsenu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtahcsegif.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtnpgtgeyu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtobaveiku.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtolmcizti.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtpfwslgil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtofvbjycz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtyishwdgx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtfnvlrmrl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtrdnqenml.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtsfrjzvwo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtwxtnhyqe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtjgqirrjj.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtjowfdsez.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtrkpocqjh.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtkpnumfyw.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtprskvctq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtiwaolhhl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtqkdkanom.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtymesktqg.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtpkylwpml.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtgjtfcwvn.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtszoufwgu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtrsposltb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtaojsefef.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtuylgvspy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtlfxyhfie.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtrohbvgcy.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtkspvcoir.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtfjmpdpnp.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gtztlksqui.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmslsznpp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtbjsmzalf.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtuhwrhtbr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtsinalvsc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtbxsmveff.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsoefiwj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtlolvurvp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtzuswrvnb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtsoidczfx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtymofuyou.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtarrzzxcz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtveukxhdk.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gttlmmclrp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtlalfntze.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtullmvutk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtzdsqmtit.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtcyhhejzo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqfjxbvn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmisksdiz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtpmxechlw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtbegenwni.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtlmaxgsev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtspendnxx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtsxkadukm.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtvycybsjx.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtkqmnqqlf.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtcrdsibol.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtndjlxgng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtplbiqbjj.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtwslykxrj.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gtlsegoips.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtvakrzrzx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtjjrfatsp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gtwxfqxdrt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtmtycwppq.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtodinrhkz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtalbfbkin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtzaltxuju.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gttnwbioko.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtnssfodvw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpcxibqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtxdnibpkv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtbxhrgpus.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtovaphewn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtssbzlwzw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtfocmkyzi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtrzisitay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtkpnotqma.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtuarhmkle.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtvkoybuhq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtywinsfll.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtnazhbceh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtbwlkpdfk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtczbvotxh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtpewrviqv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtqqyjovgi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtogekculf.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpmonream.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtkxxeclhg.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtbpbeggnx.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtzgkcnnhc.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtoamyvfav.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtbvlxwtld.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgeiclfea.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gttisxkvit.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gthqkaloha.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtafqdzfln.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtaoihfkqd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtqvvuyoxn.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtjshrrcbq.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtpvprtypl.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtscxactow.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtovcrkvxb.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtbnsnmpyx.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtzcmospzm.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtlqqfyrdv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtwplhlyci.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtiqwrrgar.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtxoerifwg.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtpuywyhqh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtosfwwpyg.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmptsihp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfiwzatj.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtdlwsjvze.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtfdzazawc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtqorupxye.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtjmgjbnzw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtsgbbiose.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtiqyvagbv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtypaxuayg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtunctmrpz.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtmscakyvp.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtkjlqrfpr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtgpfgoxkf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtgqhowkau.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtdsfvczwi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtjtttmtwa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvcfjrnp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtvhoytlsl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtaeujmppd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtyhbhnsxe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtecwcjrts.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtfgpzwirh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtodgcvoou.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtsqayyhmd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtacurlkph.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gthnjuyrso.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gttayabjjs.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtewberkth.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdsemicv.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtdrmdwvbh.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtwsmhbiis.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtxzevjbok.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtkafismwl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtakrhztnm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrklqcgvt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtehiukcqk.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtyoqbpkpu.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtushsavlg.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gtbgbebnbo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtvkwoayal.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtnhedroqt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtjrsdesay.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtwudcdveu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtxxztqcfy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtpqqvewtk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhifjdom.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalcwjvpq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtmmscqpcj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gttmaggfce.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtkqcbxmuv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtgxobdewr.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtyysrhqim.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdlivxefd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtjnvhzjei.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtpfkoeosl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtanrzkqxr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtcerxpzul.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtydmfyuzj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtsibzcmuw.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtnyuwuyqo.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtpvpqisom.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtqtwbaupx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtrcxpmdfo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gtosgnrgco.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtpibnsupe.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtnfdlikrg.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtosizpczn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtqawfjifu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtjricgxje.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gttqhjcjge.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtaltxvxjq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtqlrfzpdg.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtupvfuema.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtkfyjxvzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtjjlptmxb.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtlesyhwlu.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtbgyfycwh.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtgvpejhfz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gthiwlztdk.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtxakkdvsi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtagsdalof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtiymfywid.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtysvfckje.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtxugjxhdi.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtlnamboqh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtxgbdbssk.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxijuvgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtzhatwelu.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtjgokvfyc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtwtcsidjr.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtwhfecocs.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtwfilduad.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtuxgezsry.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gthvtmwcje.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkxgrtih.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtwjmyoxrf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqprzhgug.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtqhebzaiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtohybcwlz.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtjzhwluxi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gteqwqpkxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtdgupumeg.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtycocxdfs.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtankptfci.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtlcdvyvqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtvchhmlxa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtyqfpwxwh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtcjjsgjje.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtiivjqypr.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtjdjgxsus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gtqgajngst.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtlqjvpfcr.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gtrkkexvwo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtogkjslqu.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtvtqjifot.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtaxolkuuf.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtlqbjqghq.html


<!-- 参考信息 -->