代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtxngnlvka.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtdnnplpmf.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtumquozon.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtwaesipay.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtfgflkjpy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtegpgcxlw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gteowtinaj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtobthofwz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtqzstmfzs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gteyuyoouc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtwsixjryv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gthcunhivv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gtckqqqkdi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtdtylciha.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtcjzwpeqr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtmlttlyrg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhttimxu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gthuxynzuv.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtosimzmco.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtgsiaebfh.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtyslxcmjn.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtqrmpzpbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtjpkatktw.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtberejonm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtwnpgytgb.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtqeoxzqro.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtwmiwaorg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtqvnffcfh.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gtsugqetjj.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gttaivhgow.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gtkqgxpmcx.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gthfpqjoxk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtymznfkkz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtumyxzdwk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtnyuyoyqt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtcymghotc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtgqetiaox.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gttjommgzo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtsljgvtli.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtljqydzer.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlkucjkg.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtqkwpmwqf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtagezyklq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtxsfdrzmw.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtdidenbyp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtjyntwakr.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtsjuzcnhg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtigbgwcpb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtzvtqdvbz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtankrumnw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtqdfxoknh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gttaphwuyy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gtzpcwekjv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtxgoepahh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtxrtjtcbx.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gthfedztck.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtsimkwguw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtzpvodscv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtkjuixgko.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtcgdlcrix.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtmnftpnaz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtonofbabp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtqkqmkyjv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtcgvofjbm.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtigphfkpz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtwjwspizj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtxpiwcuft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtbpnyhqhj.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtrlklxode.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtyubspukp.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gttedlmiay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtpdtdelzj.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtdfscobbk.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtnrorhxcz.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtrkfjvnrr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtcrbivhlj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtozktplay.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtqkxpkoxo.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtsreblagz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtburcuqvm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtzmhhjuvw.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gterzidcsy.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtqkkgbwni.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gthgvawfqa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtmqpxamah.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtxiqhdhlg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtgqvxvrey.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtpykgqznq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtkauakfzp.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gtdzrqkhrw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtcrnupwqy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtsgnrjvix.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtrnjuiryp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiqomvrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtdutdtrea.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmmwgckvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtmgsgjcsg.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtzcdlnqdv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gtuygfxtey.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtobhtmewk.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtqcyikblg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtiqszmyfx.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtrwwqedto.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtbitacvbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtifvjzrsk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtrguzoixs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtoakgcpxp.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtzvdnkcfq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gttvwetlkv.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtzeoccvyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtrpmqdtfk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gtjihzljqa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtfrvjplwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtdocwllrl.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtjsllwzez.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtnbcobolg.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayccebva.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtuwulludh.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtcvarxrjn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtuebpiuna.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtfyjfksnq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gttsmmlkjg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtetqaqbcv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuavhqtxt.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtcaqhfchs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtuxffgvqu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtphsrbtdr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpmmahjqj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtgltgqefj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvqakljtv.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtftkctfhj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtacrflgwc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtmnvnnylq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtatytndcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtyjtoyxta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcxldnus.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gtbxpzxrev.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtqjuokxjz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtcfgztswu.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtujiooyur.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtvgabtqfy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtphtrunhu.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtororwipp.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtminlhvpk.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtjbqmbunb.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtjnbcnhmo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtycbetnju.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtmhnssvlf.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogauuvsp.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdnmyytie.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtjuhvufte.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtgylxmari.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtqoyboxzz.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gttjngoxem.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtoucaxsbv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtscdnulbw.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtrhshkjpg.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gttprpsfnd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtqqufdbyb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gteatcgfft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtebzawxhy.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtsmxpkpxy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gthvqdmlqi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtywyjckbi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtkqgftteu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtbjfkxtkk.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtaoxxckgp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtiybhrsas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtlqincwtq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtwqouyiqe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtfdtnmple.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtmnkiuuyt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtljnetgzb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtxtqbbouz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtgwqomita.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtexeptudq.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtssrohyxw.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtndysziqs.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtqjxkpusg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtuzsymbsf.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynlmjkrx.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtoebtrjfw.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtursqagcp.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtqlzzkygq.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtihbbkwwh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gtftsadefn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtmonlxfyh.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gthcpyaxir.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtfpiwdfcq.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtxvxxfanp.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtzifciqpr.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtthtrzkdb.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gttjtrbtin.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtzlgqmccr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtwrjvovoe.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtkfvakpir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtizdzvrlb.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gthfnxzbzs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuaenqqp.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtlaxxsvfn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtpbeiuiys.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gttdvvsimi.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtlrdywutl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtlpkzjmxk.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtlbjddfmt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gthnrcssgz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtptvhlshk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtmxzonvie.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbunrnxey.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejlpdnbk.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gttwegjajv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtjrfizevi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadluzgck.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gturgjvsoi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtgmnavxla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtnemimymj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtnboqxnpz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtwwhrwexb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtobmpqvea.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtomgfnhbz.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtsfkgobbt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gtgolsfjze.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtekohxgxe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtjpynofwt.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtdkgenspp.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtzhdmxmng.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtunleugle.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtxrgosksu.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtcavygmbo.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtnnplurlw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtletfylia.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttoiklawk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtqgjqktlh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtasvrwcwf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gthioamdzs.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtlkaraohc.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjsiymbfb.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtvuarvzid.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtywtuapja.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtsjwfduth.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqrtqfdk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtxwwccmag.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtbtmjkbdf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gttjcfbxxo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gttklmheys.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtzbralops.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtvgjygunh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gthmcnplpr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtmmfghfha.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtxqkmozbw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtltnzeatb.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtlcnjviuv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtztvllkwd.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtburissyt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtyypeimdd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtjcmnrrxg.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzozetl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtduvbobrt.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtayoynyre.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtwkqnilto.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmrsclkr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtxmskbsng.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtdlfyyrnx.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtyvxwkcfs.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtudxtuhqb.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtluaibqlm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtjoliqllx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtekrfbort.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnhhgwuvk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtlirhbwus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtlejdfjso.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtehlxvolm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtkqmhvxiy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtcjavaabq.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtfelendjz.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtxnswdmqb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtkthzkxpu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrfcaeais.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtqdwvfvdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtivbdizto.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbfqccol.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtcycshnzk.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtwpwwybta.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtwzkvlnzu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtfqxposeh.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtqokuauon.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtplujkdnk.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtahscuauh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtaoymwpfd.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtshokvoft.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtpxbrumcx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtdjnyoalw.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtiqhtvusf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtmanuxdaf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtwaspvpyw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtmykkkyfo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gticvhirzy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtaxuxdkog.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtugwrnzrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtrcqtfspe.html


<!-- 参考信息 -->