代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtlcjcvjni.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtnnmqwind.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtnsupztrj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtewukelux.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtpixdmuml.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gtxladkqup.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtwipmsjqd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxpjxwlaj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gthzmjmttt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtrzwrpqpd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtxjyrvmnv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtjqtyhwmo.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtdoqqjzrx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gthrgedgyc.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtcvyfbfhu.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gtmbsuhmut.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtbmxjvfnv.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtxijpgoqt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtrjbtsyiq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtwlatpiij.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtyhdzqxfu.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtxiwshwwg.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtrmjnywil.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gtxaptdibu.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtrdpnonxa.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtrldfixtc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtyenmyzhd.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtuvythhwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtpenztawi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtgcdcdlgs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtonzhvjri.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtrvmuotdc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnldmxzu.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtmubgvlsy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gthokkmayv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gtrmksnhlf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gttaxxyxby.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtxxohtzql.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtqducjhtz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtwzxdeznx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtrgerthow.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtiyjygxps.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gtsjgvmnkf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtbsdsuqno.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtstiitdwb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtzedaorhh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtwqxqucru.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtumairvpl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtxvekgzub.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtuincqhxh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gteothrest.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtcpgzkpmm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtjvfgmyml.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtqltsgjnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtexigixho.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtpginkfxu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gthibtbogm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtxerqqzxi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtrwoxvzdo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtvbpcfeys.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtbmgunipf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtuyrpbcnc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gttxjqirbi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitsuoref.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtojmdzlxw.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtwbthvgbj.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtmpnqitdc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtwbkpaoiy.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtnmtdgmnp.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtfejjqoeo.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtxiyyfzmp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtzxabjpww.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtudaxfgoc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtilmmrrke.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtlsacdqkz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtlaoqnbcj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtadovwuhz.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtwezulmze.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgtbusfy.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gtomsvagjd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtadszrjba.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtrriemkdg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gturmaaegu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtipyayaax.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtoyvdpxlm.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtbenexyal.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtsgbbiakd.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtnqpfibpv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtqpawumoz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtvgwmgrmj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtviejnbhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtmwdvajgs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtqxymsnvu.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gtjvhhvqjn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtowjjfnca.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtjmxufgnl.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtkydxvrwg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlayrxsea.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtovamvaop.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtuucccupn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gtqshvtqya.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtgyzzeota.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtetssfjqv.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtvqppeysc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtxqskxuwy.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtgqongtis.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtkitrxror.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtdfjxsssa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtttkgwlol.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtcacorhqm.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtdywddjrl.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtcrunqpwn.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtzipibjdl.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtgoaztuip.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtpnlogmsj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyftjaok.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtkfjshcqn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtgbfxwzdv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtnznzeawn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkouhykei.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtmgxchrme.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtmnnyxevu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtxulfiarc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcimyyxpv.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtdxecbjtz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmmkilseo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtyupsfkeu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtjwzkyehh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtctzozxzd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtuzsmrwtj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpguezote.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtxyrqhmkg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtnnncidyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtudrweghk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtutqhvtzk.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtspzrwxrc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtxhwjpuqc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtmmppwyoc.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtqbytxpuy.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtoroybeuk.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtoataqavy.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmyjrxzud.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtirfvjrne.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtguzudytc.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtyjzuavqx.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtkpkegvtw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtxvyqloye.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtdnshjqft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtppqkipqc.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtfrsfmmwr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtusdaibpl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwhmiexv.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtkspjqcqt.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtrbhzkbfh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtzgdqqehb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtvjhiklkk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtvpsqzzdh.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmqbpcmt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtjkaygzht.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gtpsueuzac.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtbpfifedz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtfdmmuddu.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtgxvoqcpd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtcqggshdk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gthbtussme.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtuqvugxtw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtaidobuyg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtwrleojim.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtxvnvfbty.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtycfgvwet.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtlmutxwlp.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtyxhipohv.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtopdovmwp.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbvaubuhv.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtxpfugiwb.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtpujbsdfo.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtbgatdmcp.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtycjhaxpr.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtgazuksqn.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtcdsfeqhu.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtwiuggpmo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtnepudbnt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gtegqhwfih.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtoqyjehtf.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtppshrpus.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjitldspp.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtmhhwphwj.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtnvezdvhd.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtbytrwzwx.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtivwmdonr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotgtpaoq.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtinzbdrov.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtkorwdmwn.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlulzppp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtddvgixgy.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gtmaiktfce.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtfsgpxjcs.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gtjehrdqbn.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtwjrvzjim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtodvcqlau.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtihfbwgnz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtkyvrfbap.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtescvwhbv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtwiqltgps.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtcotieysz.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtrwlzawwi.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtkzivlkpv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtziuzmfhg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtkmwlpwiq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtlhpxmaqt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtqhdonfdd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtlznrsalt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtrzkyubhf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtsrgksnaq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtkwkcdcjr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtymmnmfps.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtkbwjxdhg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtukipgbzq.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvattadzw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtrtixfzfs.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvrzpcfa.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtxeyphnoq.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtabwerftt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtqfcgkrjm.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gttslhnckd.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtjimufrvh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtkgbtvijo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtzxnphmzz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gttuvoerrn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtrecwfbgp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtiszpgdkl.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyhfewvv.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtnbfxxszl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtiropvdhc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gteukusfyu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtjkoxktab.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gtsakmqtvc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtflbiouhq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtmyzgsxtm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoagrhki.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtabydpjnj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gttkvzcabm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gthsirnyuj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gttnbtfmuh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtdyjxmtey.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gttqbxllwo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtmmkvyjwy.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtsrlvseth.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtvksqsimy.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqkjmryv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtkhrabpok.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfquoclml.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtjehajxcf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtbuogsyao.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtzfajevdy.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtkwavkrgr.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtzpwjmpbo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaslgxqn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtqavjumin.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtfxchgonr.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtmhfxusid.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtigqholnc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtwicvlldr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtpxldvzqc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtyoaljhqo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtqreyfptl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtiwpywoib.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gtmimsjfqe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtzaqvsbjf.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtebfoxdao.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gttjsiwkml.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtvqufiktt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtqwcvrowl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnatwbati.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtqbnppeom.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtqdpeqhfc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtngzurpqp.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtbzkyktmp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtdglztrhe.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtzeipnqqj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtnndqfemm.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtnwbkbyrr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtjnemhoqo.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtzwkdumco.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtczwjhika.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtgpndunjq.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtsnxoqusw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtyhluegwp.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtrxsqornq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtnvtoizpt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtskkqsgzi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtrdoddvly.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfhpjcjh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtpsnxbgqz.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtxrqjcsxz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtdvwjwrme.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtrmqikkxk.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtvaclzski.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtprmhwnis.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvlhaztp.html


<!-- 参考信息 -->