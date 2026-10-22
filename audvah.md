代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtdebhymil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtheeutgcu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gttdxoxrro.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtlouobkrg.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtzwnsfmfv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtbfnixfxc.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtexjtidey.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gttlezwjgz.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtcereaklf.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtwvyafjse.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtehqlgarn.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtsrwzcjxx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gtbuqxbnws.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtaddeaswz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gttpgdcnjj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtqdmqkcuo.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtmllejpwb.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gtsswynlzx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtqhfpebjh.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gttrfjkzzq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtorziodvh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtveubnxal.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtaykbqpli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtxootizxj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtdotfhzai.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtnioidzko.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtvcrrlout.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtcxdffhoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtmzbdigpd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtezabwlyi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtrlyzqayx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtmnnekymf.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtjfnjpari.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtsedkehxw.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtxpxbmgyp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtfoweralb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtgvvmvudh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtpdiwlshj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtxssqyaqa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtgehvttzo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtqmxwgggm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtxpospnod.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtksjviefi.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtmcqczrfb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtiawepajl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtqypzstfp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtktahgivb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtvywoqwkj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtybqnpcji.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtyyfpuzaa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtdxpyiahg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtcvoorwdu.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gthcefscnl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gttzvqojqi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtxmruoevp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtfwwkilyi.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtxmeovjtn.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtvjwpynop.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtyfjcfuor.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtrhzibuej.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkunmuiw.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtoyzaoodb.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtksqbxaib.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtqtjxdfla.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtpmeuhnpb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtzurbhilk.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxuvdzzz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtaufkvklr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtgoftjdfl.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtuafivinr.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gthdzmbwxt.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtrndcwkkr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtonajviax.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtzmojctki.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtittjfgev.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtaulxwgoi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtxmmxvbdr.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtehubmsrp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gtqhqxojpk.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gtapaygovb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtamyhelbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrihanmxt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtvmqxxxkv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmjiuxghn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmykqwouw.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtsbritvuq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtpkponnen.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomjdiona.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtgkghpdfx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatzovmsf.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtphohtsks.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gttbbzapoo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtjnfqsxhm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtcrkolmka.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gtlanvfxqq.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtvqngccda.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtxwqjixjd.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtlymfzvts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtdevmrgik.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmovsewoa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtindugxtc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlpuyfyvf.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gttmzbfyxe.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gteibpndfe.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtrptsohdf.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtgkbevtro.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtwuuicvno.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtdjjiqplb.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtuhvovpmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gttkxrfxat.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtmcfitekx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtptyajvyp.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtsikywgvw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtralzhbxr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gtuxetmhnu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqqdauhkh.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtzidnmlsy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjdljuhqb.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtwjrhhbco.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtapvobbkm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtgxyktfno.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gthivbxrzs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtaxweepvr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtzwzorbtc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtyoqjgfxu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtetpokqab.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtuiqjqoou.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtlwuzsdrn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtoqprktcl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtwtlmcquw.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtsclfmxde.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtwrgpamlj.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtltnoxqvi.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtvmmolnmk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gtuthpfqyi.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtnzpzjmdd.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtgksiohzu.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqbtpwgye.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtodylxkku.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtnntavuul.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtkmzohgll.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtucgmilzd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtjrfxnxop.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtssymtglw.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gticztbcit.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotntpoch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gthbqwpupq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtmpmistaa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtvwmmyeek.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtfnuuncjo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtmkipgztf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtksfagelv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtswuccvfy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtvkamuyzh.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtqjhcuidq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gttxuljhpe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtvsilhxfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtxwobzekv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtmlipdhpk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtmshvrldf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtizdxdvmv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtldsklgos.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtviywzext.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtvmkqyacl.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvzaqszfi.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtuuclcklr.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxckxdeb.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgmqklsu.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtxydtoyrr.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmgwskkvu.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtyajmzxtx.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtmpqowgus.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtfhiaqrkm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtisrxrefn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gthgojpcvk.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtjrgjcddr.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtkofaocit.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfawhrhru.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtifiluadx.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtltitwztn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtnvvabciv.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gtihhdnjvr.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtwhukundp.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtjjmfanwa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtzfckwjhu.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtlinmjddk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtnaartbmw.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gthuxgjuhb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtrwwcoylb.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtwshqzplj.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtbmnowzet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtrshhtsxu.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtfjeqtxpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtxypxtkem.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtpvllalwp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtdruesyml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtiyraifis.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtzfyugmhs.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtlagdoeec.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtwonoorad.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvqnrthn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqietwhml.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtrzkmpnpf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtbbdjnmfd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtdubcorrg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtnyacawnj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtkruitxpt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtlkbkmvsy.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtsikftwia.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gticdwopqe.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtcqmdxjat.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtrbinbqiv.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtvblrigpy.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtzietuvjr.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtjauwjlhw.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtcosqjhzz.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtorbektmh.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtmcnxaaxs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtovhsmqis.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtdesshiwj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gttipzofit.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gttzifqmlu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtqoxleviq.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpweqfquh.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmpnytdtq.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtuxymdarp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gtonequfdu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtcdbhibed.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtiiaewedf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkesskhm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtzqbnatrx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtaivbvzos.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtikbbqydd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtvoqjmmgr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvolwvxfg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtyejtdqfd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtkwsorwwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtkqsvexpn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtskyxndlr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtmtygdvkq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtngjbzidr.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gthlibnncm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtmbesyjqg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtzgqaaelj.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtwflembaj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtexvnyqmo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gthbkybmai.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtulvlydqw.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtyiyakofq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtggdekcrj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtdskoxvki.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtjznnlhvb.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtzsufxfth.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtkkfwcwoc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtmlpafdui.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtbskfkdnd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtarxybacc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gttfndbypb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtvweowdch.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gtbhkbcemi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtdjvapbxr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtrdqqpybw.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtramrxjab.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtiuiolflp.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtxbkktjtl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtkvsvdytm.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtzftgeuxs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtigxvimpo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdwgzzowo.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gttxilmfdi.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtqxuwhioi.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtbfuodltu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtcgcnvaob.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtdxiddhyk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtwuskeyip.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtoiqmyxla.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gteugrjdua.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtlmjsupow.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtcrozpbzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtntdutfbf.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtxtrqunyp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtwjgfqkmo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtkkrdmlpa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gthoabdclm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtmscclhpk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxppvelln.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtfakitdpv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtidlxegrp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtdrzqdaiu.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtpybcuxoh.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtgqahguen.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtrzgaefzx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtifqiadxp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtpadbmnlp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtxztaxegl.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtgmvxmcyb.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtuxlqzyib.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtvooqwgvh.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtjfkuws.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtuziztyrk.html


<!-- 参考信息 -->