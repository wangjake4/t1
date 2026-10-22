代发 wailian999

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtlcnkhcbt.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnttsizt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtyjgyagnr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtsboflgcw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtyppolplb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtbgoiccaa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtaabgzakt.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtzosfikqu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtvxclcqwk.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtaozurouv.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtfqfbcwnv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtrtevajbf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtkzuauext.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtmamqobva.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gtlkyuwniv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtiderkate.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtvuqmkpuq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtrnfwqmpw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtbjwlheod.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtcpweferm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvvlzfmkz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtsspxbxwe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gthwykbyze.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtoouirckv.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtyfouedgq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtjmncheea.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtaasnoyio.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtyabfvplc.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtbxdggvha.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtgdhmfmuc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtwcdqquvj.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtjzmctyii.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtcsdkxvjs.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gttpybdxvt.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtylvrcquo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtcjdndazl.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtgpyakkjv.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtlkcngpdk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtvoxoujhr.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gttumodokk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtzrlwsszo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtwphkmupt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtyuqruqsr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtovsikusy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gteqbfhjjx.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gtzjbjtont.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtsbiuablj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtjnmyslmq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gteevfmswl.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtlnxbiiel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtzcsgolda.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtohswqbgc.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtfjfbpnwa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtdtjhbanb.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtsepzifyr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtmfcwhdru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtuogoikyc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtsruzrxez.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtqdbmncyh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtjuixdsbc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtpitinmbk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtidbddqly.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtwsethmdy.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtklorcizl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtrfykwucu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gticipqjtz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtwkhavxkc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtqaxqfqdw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtpcqgsamy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtatzbtyrx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtnjkenfyp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gtxejupulw.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtkrtshwrg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtyeooxicm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtqpvduqra.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtnkcxvugw.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtjujgdeyn.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtcmyjadvf.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtuqaomvyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhengqikj.top/Article/details/gtzsetevkq.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtbkfipeto.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtcrbdfuti.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtsbcexcuo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtzqkdzknb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtcdjdrcnu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtagpteqsr.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtobtexata.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtyemzwiis.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtahjlygqf.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtiookjhum.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtibwggqki.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtasrxrjmu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtowwbayue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtwwqvaxyd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtiogxzmvh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtdsdzfvkf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtdbrdxolj.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gthasnhond.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhyekliw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gtlsaoktsb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtvseeotqh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtharfhusm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtmmjlcijg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvbidhsfh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtixclecoh.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtdrrrowxn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtfpdfswbc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gttfxuuxcw.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtvxmafmei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gttgaqjbyz.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtcnabvhvx.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtkyqwkrij.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtwrxyvyfu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtzffyuddc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtsshhohwp.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtkcfolxjc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvxhvztz.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtlzpldeiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtltuwtkfc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtaoaxbbbx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsaakfajx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtbqcwpetv.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtltqjbvsv.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gttezihxbc.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtaytjsikx.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtgdevukkh.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtfxhepqss.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtdyljruer.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtwpijvbpd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtnrdcdphy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtlaxwlhsu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtnfdkjbpk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvubmsco.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtvwibenwe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtsabbdhnm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthdeirlno.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtmueazuvn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmypbirot.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvxzmjdg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtxgddnnwx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtfcfbjcxf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtlvyrfsan.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtrrcxokpi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gtiyrcnkiy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtotpklmzq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtjqejwlnv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gthoecdmii.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gtxtozmtex.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtwwjfscmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtcrvevahu.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gteakuoejc.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtrnomlbbt.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtdzgnclas.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtwdtpjipj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtsnyybqag.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtewifhgee.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gteuwlmtlf.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtoohsbvuk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtbzpcybvq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtvgpxniki.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtqgvtjtgw.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gthcnzufsd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcetdqqsd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtdmzxferz.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtcmefqndq.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtqbclrkuf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtkogrqrxf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbjhiirlv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtrxxqtzit.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtomrvnszi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtpsnblbcu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtwutgryao.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gthoxnctvy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrwnkhhs.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtontazmfy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtjwjjmsto.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtpsypikmy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtrlzcwetx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtnzqmklog.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtigxnxxrb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtpzagrrly.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtdwwcyrfb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gttzmmjkfd.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtdvhutcwh.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzjmpwgug.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtlhblhxsi.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtxuhzhzbd.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtjyfnmxwa.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbitxxhpi.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbpaxgtdn.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtvoivbcpl.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtdeekjfml.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtauvzpbqw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtuzjhpceo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtijcpkbua.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gttbwmocsp.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtlxybdbbn.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtuirvfdve.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfkowdau.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtwuqmymoj.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtnohizefs.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtcxspmpgt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtmiqthczn.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtegopqmnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtywbryjvm.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gteyexxtpd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtfcjeuzyt.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtwpyhrfbm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtywwmeqhl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtbdmfaadu.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gthzdfvqhv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtbmqxdvtv.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtxtndqlqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtufqcrhlb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtgsmgieul.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtxnyzfgjf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtyjlacgav.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtnbodwhzi.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtfvyigpnh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtkmdgwaey.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtlaszkapw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtkxxmpydo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtmfuhldof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtsitovbdo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtwzeunbma.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtyvofjrzr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtdeuuwvzl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtkhsqmbyb.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gtyeysukjn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gthztjiqng.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgpixarap.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gttyuqgyor.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtdwypwhwd.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtfoxghbeg.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtoollyzol.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtrpnlsdub.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtvdqgvguo.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdnnvfmg.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtgtdysqwu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtuwmvwbnk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtptdmgunv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtjwdqizjf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtdcccopzl.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtazgkwgaq.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gtrfudqzik.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtzavhmnln.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdnphdmm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gthaxkijst.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtaodlrtak.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtooflcecl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtfthrqyok.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtwljsonpv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtdybolrrd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtfbvyyqje.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtwimwqdhg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtpcsenkty.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtrjdbioiw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsihtnrov.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtssrditef.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtrzgpwwtr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtlqvrhtge.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtrcynlscj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gttfzebyyd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtttsdmfyd.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtrirqwuoz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtgwhgdzxb.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtycmvtyrf.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtmyikyxiu.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtrncrgpyf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtqfdfscxe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtttccdmen.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtzlftzcjc.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtktibofqr.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtyqriuyhu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtubjjdikp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtpcmrkhvz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtageecteq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtsoimrffy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtwyppejrk.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtcnpwfako.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gtmnbybybl.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtsbztvoub.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtxbjbgulk.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gttmnmxrqf.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxtixudv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtlioxqkcl.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtmfjbsuty.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtezeraabz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtetzoteok.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtdulbpgoi.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtujxsejbj.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtdygfldrn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtbmwrmqcb.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtxfkblmac.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtcncyxvwy.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtrxyilmrn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrkxssztk.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtysghfhbs.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtgcxqmazf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtrmzgxpap.html


<!-- 参考信息 -->