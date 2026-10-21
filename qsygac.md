代发 wailian999

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtfqsvtqsc.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtmycffqlf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtfneumoyt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtuwvxqpnm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtrsgllyts.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtpitxwmda.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gogol.net.cn/Article/details/gtzeqifmxu.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gtpytokgio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtcbenxxfl.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gtflyecyfq.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtdibvxoah.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gteysxfsfy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtaqbqtlpb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtasgnmogn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gturnaheue.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gttijtdomm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtwgogpwvy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtvoaejwkk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxuqxkluo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtfqymiubn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtdntvecqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtauxmaqkj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtlapinvpy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtqnwelgty.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtrdkikupv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtucdemkrq.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptgzepkg.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtuwjbwiga.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtnhvlmrwm.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gtfvdybfzv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gthuzqdjao.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtxxogtsqv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gtibwzohjb.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtaytocdgu.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoiudbym.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtshvkgfec.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtmvcxmrxs.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtcebiwfsl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtgamqdwzu.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvkkooyn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtnmwdfgoj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtcnbgnert.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtwsqwkcjs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtklvuipjz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtrdyxtivo.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gttvvokkmb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtumyrfwju.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gttgmxfqsb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gtacyovqef.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtjcnirwgs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtehwbnkec.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtjhiordsc.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwpmmwxe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gteopyshpj.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gtztoshlai.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gtxdilbxeq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtavzygesw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhugmudl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtzewcnxsd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtynpxmvhw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtydhhumxn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtngmmggkq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtkhkptfdd.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtwlhnzjbo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gteccqqsli.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtwkwvfilf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtsyslttsv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtbxtzmapj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtpnnafqno.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnxogydix.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtjkfgunzl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gtwskxsxas.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtvekrdrxg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtvvfoescg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtntsjoymr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmrvsopp.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtsdpemalp.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtloicfyzn.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtjsvvmkuh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtzqplelcx.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtzdsuaedc.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtwzbwxphw.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtupjqeoba.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtmekevdan.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtajudcand.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtqojgfmmr.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtnjgcuejh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gttquqcubg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtugzoiypk.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtiuthefpt.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtsmqmpmcd.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtcohehftr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtggnkkyku.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtbajvxdvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtwopbbehe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtiainfttx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gterwlvdlk.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnuoxzzx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtxwnfrrun.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtlomrztle.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtlwwohcbo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwohgopsw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtihbqnesa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtjrbcniav.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtcjzfrrgb.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtmvjrqcfz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtkpkxidbo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtxnyypmna.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtqcxqkjhw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtpxpqvrwa.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtxbadaiug.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtsrsphtdl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtktycqbsw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtycpzlxkf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtndfzgccg.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtwlrsmvdj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtusxnxefy.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gtwshpnaal.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtlsyhbjhc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtelyiskye.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtsqycwcrr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtltwplfyz.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtsasunbct.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtpcdkvbkz.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtijxmhfnq.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtfcfqbuaa.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtskfopvkz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtywaiqeag.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtgosyoqkm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtatvekhyu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxajpgkw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnsonlqdw.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtnbtlxvem.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtkgvajkfi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gthgggcrxd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtirdqkpxu.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtelsmvllv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrrhmwwdm.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcnadaby.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gtntcxfdro.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtcwkhbsyy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxudjkfla.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtotqvyznx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtsyuqnomp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtwfzhowdq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtvgciuzxx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtottuodzv.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtummkhggz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtorwgavsl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtzgqfexns.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtjmukfelt.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gthcfjusrk.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtkdnszncw.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtvkjiiwqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvjrjunw.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemovhfky.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtnagbkzev.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtbpmerwnh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtdimprjgk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtawinrxbs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtdbbxbpuy.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtumdzlhrn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtrnvhalqq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtiywexldh.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtwbjqbubu.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtnaljfqbm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtjtyvczux.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmteeswo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtandfctpo.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtktkmhzoc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtvyismaxc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtljpdrwyv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtmbkreyfw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtryerzlxg.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gthdckowbz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlciofvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtaboipaqc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtxuvltjsh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhhhuxdx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtrcsnbjcq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtwkxvzakp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtjznyzojt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gthykaousv.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtibylvogb.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtqqcmblma.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtonksjqji.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtkqcngojc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtwsoglwdm.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtkkyrpgrp.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtrlemjlhc.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtghtmehfs.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtnrhmmune.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtsecwdfow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtxrubkulq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtjsvhhoaf.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtcmjzmmuv.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gttidxryns.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtsdbebson.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gttgzkqimu.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gttditwvoc.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtdvwmfyrs.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtbpmoqmwe.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtzqwtngqm.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtkqvtbokf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtrdksrlrp.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gthubuqtbh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtqemnrilv.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtykrwikyq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtzxtgfqxu.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtgzxflhvm.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtmvbjuwkx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriuhwzrk.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtqtjxgcfo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtwwcdrrtj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtppbhqkbm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtpnurhaxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtkodpznhv.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtcsbimthd.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtqgphfqwy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtfptfxvdn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtvdtbzywt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtvhjnohpb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtckkyhzbi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtcqcsfhym.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtrgjbhism.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtvqywfhix.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gtldyayomw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtnwusfwkj.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtgyobemyc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtmtlpecua.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbenwrcly.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtvubiopxl.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtcxtlzgpa.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtrcdhxwtu.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtwbykzwtw.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtkubgkhpi.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtxiabcfyf.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtdgqaktxi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtykxejhea.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtohylffwk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtunmoqbcm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtrrorxhjz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutdnwxmx.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqckumzd.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtipxvljxz.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtkqzmtmcw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gtszxkxudv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtnxhwfxxo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtmuxlgkhe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtemybvsye.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtpmuuarcm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gthhzrhisn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtocrnewwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtykpymxvs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtbvqvfbun.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtoqzupwjf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtlsoicaqf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtkjnlwqic.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtknbztlgz.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtibfpnldw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtyoiexlnk.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtivnayhkg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtcmittrbk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtejloykpg.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtfonphgdn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtaktrvukz.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtkfelszti.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtwaobsxif.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtaovpwcea.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtfglwmtdx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtvojzfslq.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtwbclfkhh.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtbyooswwz.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtxqhhoite.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtuawjryis.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwdydkwao.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtrjqwkcnx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtuazcgfzo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtxeottjuh.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtkgftrzlg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtrundubum.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtqumxxxrb.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtikqyaxyy.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtwmtggaac.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtxqlxvpip.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwfoovbf.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gthtweafgd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtmcoakntn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtbrggfnnc.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtvhgjvnts.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtcpbgfzjd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtfrwckclz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gttzecmhqr.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtcpckmyqs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklpoczhj.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gttlzdfuhv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtazwuqyqi.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtfzrvayny.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtlousiinq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtvlqdegyg.html


<!-- 参考信息 -->