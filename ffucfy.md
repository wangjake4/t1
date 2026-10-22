代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryautzxc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtfgyznqqe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtpvxbfdnv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtfmbrwjzt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtriocnuoo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gthrhgetoj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtspgvtiie.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsziojlps.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtwqmwosqy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtlovqauua.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gtrgmbalno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtztnnwzwt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklqdsrkx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlcpxdekz.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtcxwqmqka.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtblxgxkkj.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtcbmjvlry.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpzgbxpi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwydkwkzn.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtbgdletpu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtsptbbpvy.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjuedrjvq.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtxcanowjc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtexznxdty.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtdakxmgxq.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtkhhkstbg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtaqafvjqq.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtjkwamffz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtqnxzdqhd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gtpexiemft.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtckigpqtu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzccvsrw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtyjpwyzvr.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtjppjtkhj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngqnzpto.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtdyoqwvsh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtbmjudqdg.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtvuanwzgs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gthdkiecis.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gtzfcldjje.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtqqsdfaji.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtphcvbirw.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtzgwxtzvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtksgnoajv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtznveynxy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtihrgpgdc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtdjcyzgtp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtvwslmmjw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtjnjjbofe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtawuwhrgm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtmblxnylj.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtegucpbvn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsqltmdm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtneoxaaqk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtlwapwydd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtvvxoijms.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtzefgmldp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtereiqqyh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuibgili.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtzyejvknc.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtorviorsp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtwptypfre.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtpjrekwgk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtuytkuqwq.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gthryehdpu.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtrvuxslzd.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtbeiwhavw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtoukkpspn.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gteqltjoql.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtiulybsxd.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtgwpqhryi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtotrmbaor.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gthqnmxdhm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtgmwsnwoz.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtvedzemgj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtsbkcuttq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfefuxhf.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtjbhdhiup.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtkfopskjq.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtsdvnpieu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtpowcdaqi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtoxczzblr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtctospyqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtixrwkiwv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtlboqqtkq.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gthhpcpmtd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtmeznyonv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtwmcanfmi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtipejkhtp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrqvhswvg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtnlbahhlc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtocjravvi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gttuxqgguj.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gthxrulhxa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gtqnozvqhq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtowvrcmln.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gtqnvtdsgi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtogiowhwx.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtvhtnzuse.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtcmhtldxr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtfcyquedb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtilprpfjp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gtitimgvkn.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtplfwgifj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtfmfefcnk.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtfhyzsfyw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtoqxydbnq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtovvkimcr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtqqaifmbt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtglllbxtn.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtxoapqxtb.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtwgxrlask.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtyulnermf.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtzknscgqx.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtgwyvyxzx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtntgiezed.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtodbjhdxz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtadihxvbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gthazaqrjp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtvllzegei.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtflyskyeu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gttlfwosol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtpczcwlpv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdrrhnsu.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtliqzuzok.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttkvirrlj.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtbwqepwhp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtlzgihlvq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtbflgoroj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtzvxkfcmy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtikotfrkt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtwrxxskbg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gttzoufevu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtatbjyetx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtherwgdca.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtjhqlyhfw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtfbqxucqw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtacxutmxy.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwdvttwgd.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtepfkoirf.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtmoxzjwho.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtxikgdkcv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtrvobsesg.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gthkmeqtyt.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtawpdvkhs.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpawdddhq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtoszexzin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtuuqdowni.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtejotaaau.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzcetmfp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtnlhxrdbf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gttjhxouig.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtatxsnbdi.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtrkucagyu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gttlzujqkv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtsabqodlv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtvhvztwxy.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhsugoed.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtnhvpaioc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtshlbiqpb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtsvrbtpwp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtadotlvke.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtxguzhuog.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtocxvofpl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczducdav.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtdhyohdlk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtlpxdmyya.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtyutvhbzf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtbbbabixc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfdtcoly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtdemncmvx.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtpgpqmoiq.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtkfdfidlc.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gthwweydjy.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjphwgaoi.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijtlgzon.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtywysecig.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtusalxeoq.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtlizrfkii.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtyuacoyjq.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gttudoshdw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtpkzhqbbg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtotzfpzod.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtcbijavnt.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtxuzryoms.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtrwvathqg.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtjgwwnypj.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtaqrgcklq.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtibsvqlmu.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtdmwhqznn.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzccjjvh.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtqckvoqib.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwtyeoan.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtmjxwwaob.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtdrynrgam.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtbzdplwxm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gtgknhlkdk.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtydeosqrb.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtxoimzbrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtijkrixcx.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtrlpeexew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtrsoetbgg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtezdnybju.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtehqudtir.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtydmltuvr.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtuhxllzsn.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtkdhucpnt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtfguwknla.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtrumragtg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtkhoxqcfj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtnrwpxcwr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtyrmbybak.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtmegasinx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtilgshsyh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gttilglsdo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtqqzaulkv.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtxuhiaweb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gtbvwxzafj.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gteplkgwut.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtjfwmtjay.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtdrjuhple.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtyywqjwwo.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gttdmzyaow.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gturxrlubu.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtlcsurjli.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtfeqrnbmb.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtzmoppref.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrhqozarf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtogkytugp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcjbjezdf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtvfkmxyyg.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtijjulvyr.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtrkocvhvt.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtntqafpbn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gtjfrdrgaa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtfbwkbvuf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtyarktvuc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gthbnpbbpp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gturrykouq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtgiwkcjuh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtdjrspkqm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtxvlkvytg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtawbctqgl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtafuzmrfh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtjfrtfdmb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtqreyibvt.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gthklevmes.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtcejcbogb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrwoefoi.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtuorwixha.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkfnevpqf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gttbxbmgir.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtnqkbpywt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtnawrdrvs.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtiztzqaub.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtebktxhnv.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtyodwuftx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gttklctnet.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtibrjbwww.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtwszcmrau.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gtgaryzikc.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbqxwkmm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtbtfcpfmi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtknhtgyue.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtkueyfgye.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtswuheiaw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsptifknk.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtnwyybzvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtqnvqqamb.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtszszzuuv.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gteyprabmw.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gtwsszodkt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtrxxelzhk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrtingyoy.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtekjmlwkr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gttjdaouvj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzyroyri.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtykkmrlve.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtawwantsx.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtfsvdqhtc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtvacxltmi.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqghesqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtngdynfhb.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gtvvgcvkph.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtyctgeopj.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtbtqsvofl.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtgptyykjl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtjbowlrjt.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtwnbbtygq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtdwspcyig.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtiqjfsalc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtwlnqthfo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gthvkxgapd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtmudyeglh.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtxypagxbn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtfevkqwoj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtknzllawv.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtgmczzzux.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gttumrxttc.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtvgnohyfx.html


<!-- 参考信息 -->