代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtfykeuwvz.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdmyfqww.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtkueizbei.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtqyyohxey.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtyaruswfm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtymnhvjse.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtjbhgvggb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtyradwkiz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtqtcppzsn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkbdevja.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtfnnvibyk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gterxbouxz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtbwsrxibu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfukissko.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtlgplsiou.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gthrityiyl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtrdrzqlzm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtdvfvpivw.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjeptyez.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gticzyamng.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtcgkxbfev.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtoewtesmx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtxhtlaejf.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtiowfymiq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtyvpkhfwp.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtxvhiesdv.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtwctudmsq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtpnbuxbqg.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtpvrcbver.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtvrikxczd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtucyeavts.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtuigaifwp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtgzhghljj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtdhsxcpdf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtsrfnsiyk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtdeghmjiu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtcgaklorx.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gtgucyqgyj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtjrywyait.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtwjhgxmyl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtmfqgjizb.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gtbdozheng.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtkgnvxmqm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtariqxqdi.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtjpvkyskf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtdlcesspq.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtothianlo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtqzboruob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtqjfyxgcb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gttlylneca.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtgllmpolf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtqzbcwwll.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtevllrbma.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtozzglmgt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtvpeayogi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtvotvwvxa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gteglcrfbd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtjmjahhfj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtgdhpznuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtqcwbtlzf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtlqmaefuj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtfzvemvzk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtasyhtwgh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtkymbzgjv.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtepxzldes.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtmyvtxrxb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtqppknpld.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtqhmctrvc.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtcuwoncpb.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtdwbhicrg.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeyluwzp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtkcphhrze.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gtcqutilal.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtgpydrwfv.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtiaifible.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtmtsfcikt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtcymstcfv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtohhmtdta.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtlcbymjny.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtfqjgdlci.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtqtkalmsb.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gttcaagqxp.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtvooeowav.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtwsddnhqw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhrttafl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtbnpinecj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtnevmbpex.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtbltwxjbg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtfzaybgyy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtvjysvozq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtwxcidqem.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtludwtgjg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtgtwpwdkz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtwympfcnq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtftrwmolx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtvwdfdjyv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtolzkvlhv.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gthxinilyi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtkhfjtdda.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtfmggszoy.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gteeeaysmc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtboopdkgy.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtaxfapehr.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtbilwklqi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtajiikfvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtwpzfdswo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtofhdpugs.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtrhzkmavi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtlbpkgobi.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtsmlucurk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtypahsfml.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtqlzwogej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtivmlzcqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtrhjjlweu.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gthlxcqbvx.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtdvqrbmvp.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtvyochsyo.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gtkvvqfxme.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtzhychydg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyhckasl.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtnlpzljmp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtrlwneszx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gtezlkdujw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtbzzbpldt.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtqudmookh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtjznugart.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtcuwvuyyd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtviudshpo.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtovfdsjuy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjfqadrad.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtaptbhiez.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtxhuqxzpd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtwrhkgtwv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gthsodutry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtaqxnvjdy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtvjqoihry.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtjqppyile.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtxgikryxi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskelpbqw.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtcuupfbjt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiwacjsn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmivngthu.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtmrutgivv.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwscurzq.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtxplksmhn.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtxnumvrri.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtrquygvdd.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtqdyvqlpx.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gttxffdeok.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtorcpsfml.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gttnrojusy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtuyzkbbsi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gthhvqeeek.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtdaveypza.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtdocqrjch.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtgqtqzzqw.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtobttbgld.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtrzjixxcp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtyavuowei.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtggcuyeqt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtiefqotuk.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtfcsctvnd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtztgmdtds.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtyjwiaaqb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtmgzfzber.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtttwtuone.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtnrjcjaza.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtjhfooggk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtlxhxhgln.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtkvhintbl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtxeqbkisn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtquqshnxx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtkucacqqs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtqkyqswdj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtzcoteimi.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtgktviagd.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtawmhpqkr.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtsbmhgooq.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gthmujpqje.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsfzpwkl.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtniboioyi.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdbyiwaop.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtrvlxqntq.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtkxsblbee.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtezizcqdy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmzavzjl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtjvetlefk.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gthkzjwmzr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtgainxdjy.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtfbbcnoww.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtzubkddek.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtbpfwmzpl.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtemajmsuq.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gtiqcglrjb.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtzgtjstdw.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtlirnffda.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtlvgimxhy.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtjagkqvdb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtjelqmlni.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtjvlnbxnc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtqjgjlbbo.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtssidcclf.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtwgnwadan.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtrdlsafjg.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtiuypugsn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtcpecugwi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtbfkcvmjv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtgjldhgdp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcruxsrua.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtblturipj.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gticyklarb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtqpqrtbak.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtxsbqgcam.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtnctgffwg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtoclhaxai.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtfvkmheck.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gteibcgrek.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtopmqhjsh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtlvbjtpqo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmoxfmnv.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtqrtpkqtb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtysquxweu.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtdjfysqcy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtzrjdnpsp.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtdrztqtyn.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtyvzicbbx.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzbgqgwiv.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtyzwkiioq.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtacbcqzel.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqwlpnmc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmbbfkvv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtyvlgtonu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtkupzdgbe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtmyqhzxsd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtauqcrwkf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthvktdsxm.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtwcakgkey.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtrgtqkwqg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtzgjcwfml.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtroftnmrb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtalrfgkmq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtayoqqjir.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtycmhplyq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtvjnhiyjx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtlyfbgiqd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtngxqwewo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtktczokjz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtylpmbvcl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gtfebixsra.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.316326.xyz/Article/details/gtfarrvlpu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtnvwkgdhq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtvkgjmper.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfklftmsy.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gttlwssobz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtawzjxcij.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtoobmeexp.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtggoyanai.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtitompfxi.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtqsxdup.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gttksygacu.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtnqxuptbx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtnhfxygzo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtvloadwiz.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtkhqmuedk.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtoqyiclla.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtmeurupzv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtdcztuhff.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpsvrozry.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtdgonlgzi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtxtythbrb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtgsappqvv.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtahgdrvbm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtfiqdicii.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtitzabxpj.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtdutzyueg.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtgicwlhux.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtiqesccxb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtswgzqwfo.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtipnrreiq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtksotkcfq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtgsttnmxm.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtswpdynnz.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtipprkyty.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtpefrarhf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlalacfq.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtrvgjhxgw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtviayqmzg.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtsicdxntw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gttblfpadu.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtyaokfxnh.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtcibirxsu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtjnsojpwl.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtjijveydh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjqsavode.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtnnxwdgax.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtacygmemw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtmpkhbzli.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gtlcfxbemd.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtomvausyr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gthjzpbhqx.html


<!-- 参考信息 -->