代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gt2xtbcgfdk.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2bnaaoqzo.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2tbptjalh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gt2zsrtorxg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2skdblwep.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eiokyupd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gt2biyzhkml.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gt2iaqioanx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfzyqgd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2kysvcvim.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwpxuhen.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2zdrcesnw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2bjrktfni.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2xqqfrwwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2bqnwpgah.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gt2cpovcftg.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gt2ahyayzia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2gwogqtry.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzoraznu.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gt2kkfrfulz.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2solpeuhk.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gt2yobqolri.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gt2votdrnqb.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2oyzsbyze.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2odtgqsqs.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2jdtjiofa.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faeagtle.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gt2jnwvoqcq.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gt2mkpezzol.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gt2irbgtaik.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gt2hpxmbdxc.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2kvgqomda.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2vensxleg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2kxjtaxmi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gt2mmquoeyf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2ugrgjrwg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2rhzpetep.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gt2rcavseuw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhkaqhho.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2zwujzktd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2mqlazpbu.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lerxrvib.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2mehwmhtp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gt2zezwicpc.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2lgfdphrm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2viivneup.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gt2psimhlqf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gt2chaqdtyv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2ataunhia.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2mjwxajwq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2ksmddbws.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2loullxyh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2dchnnkrp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkigxilh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2hdpygdjd.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gt2ewwgnyup.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdoxnrbz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2hkwttnic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2bwhdvrrh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2pqauytga.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2wygutmfb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2szajzdbu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2sedmzbxx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxjglfvm.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gt2hrpikrzz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gt2hptfvmln.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abvudoaa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2otsxfbcn.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2fqxujetb.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2rpbsjmjo.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2meudrquw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gt2tidxswif.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvxcbshi.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gt2umhrmmsu.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2mldscfca.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gt2htzsnnfp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gt2osraqcxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2dgljqiaj.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gt2nyluvfal.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gt2dlubdraa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2glumqrvi.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gt2uecnlxgg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ruptgszo.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gt2cjbylkaq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gt2nfsukiwu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2qxqiwbyg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkzufvlf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2ntauncmg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2ihudigml.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gt2npzdgfem.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2lfrqjzyb.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2ypsfgjln.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2mltiyqcg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2vxiefdos.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2adzzpwyo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2zwrxvnxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2spfmcltw.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2gpmijqxa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2aipuxmmu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2umypjzos.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2qlnrzeaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gt2ggmsavdq.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdxgdpwz.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2hdrenphr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gt2otzhcamu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2mlkfjfao.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gt2jbfmrqek.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2qcvbbrgp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2vzxxtexe.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2giyiuhyg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gt2drfkbmdc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2ucolstpd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2hmypspvx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gt2rmdviwpa.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2lwctaifa.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2gzalciku.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2crgitmgo.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gt2ntvzhbkt.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2zpvlxfut.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gt2sikpdtmr.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gt2mqqvxjdz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2zrdajkqz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gt2mqnmsnbd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mqbzyjjt.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2ankhlulq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2axtekbpi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gt2djzzecsw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2kwwtzhyw.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gt2seodlgax.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ixsxyrky.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyrbughv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2tfzjgdmr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2zxhnoanj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2gdgucsry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2jpfgjeum.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gt2xrwuucvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2ojvrhlvh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gt2uqllcfzy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2qnftbhjr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sykutiru.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gt2znfszxcq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2exbvjbhu.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2fidmbozl.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2tqlmptsa.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yswzdgsb.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2jqbgrmwf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gt2bzmrmuhj.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2ljbjflwl.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2muizsolq.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2nvobcfrv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gt2sbyzovsu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2onxhplmi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2uabnawal.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2jjyutasa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rinqqwme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gt2xdfaozlc.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2byekjjwn.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2ymiwgwhz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2hnuzcwke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxbxrnxb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gt2efzqpgic.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gt2uuuiecpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2sjdlenlj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpvwasgr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gt2czyjbmqz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2cunfxaic.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2bkeainlx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuhifnkm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2cpwowevl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2ogupkziv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2jkyzpjyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2gpthxdma.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2tztixccx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2ugtglkxl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2voodyplw.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dailmger.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2apythsdl.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2etlqhheg.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2ucccfnmx.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2nejhzgqn.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gt2bolakwul.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2tfhvysqq.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2urhbwgyn.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gt2icbpsrcn.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2ovywzkct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnyakyyd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2dspiihkz.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2wlexrvlm.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2yjpjogyo.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2gjreseym.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2rkwsttay.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gt2lsxwsrpm.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qutnkvsc.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gt2ypzpknwc.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2djhrugip.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gt2hqbtllam.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2fetoepvi.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2yngzinrx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gt2exqwjukq.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gt2nsrufrxg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2pcjwbamx.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngvynwgp.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2czpmyknu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2jldgdvcr.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2nfbytrgt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gt2etjwwvhg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gt2gbmbcucf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gt2vuszxzgm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlewmeej.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2dhhthynq.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2tzunkrny.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gt2cmcchhbh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kftkbajc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2poojiavk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flwshblx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2cndvnfpc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2wlkckrlz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gt2xorvrgif.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhjygywb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2hxezeuam.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2jbvbrghq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2onrdabrz.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gt2yiwfllws.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2yafvjsmx.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2esaflrvz.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzespvja.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vtkcmxfj.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2ufeawtgd.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2iyboiesk.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gt2fakpfzzn.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2nfnzywou.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2xswlyxqz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2aaibrtzo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2qvxcdfsj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gt2nzuzxcla.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2hftkvfxh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvmwdtm.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2ehbxdcwu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2goolzwhw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2iijnwuro.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gt2kuvdbcqh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2osysteoy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2mqppvxaq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2ozubunpi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2waubqawd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2hkkvvjjg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmvlbpll.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2vdbhvnqj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2csdpngue.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ztdmdscu.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hkoipaba.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2vilthuun.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2jkvwjqvf.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2bwchhfoh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2lgwnunvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfvexnuj.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2mgvfsjgd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2zcpjkwjq.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2lwueznvs.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2oduroqfq.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2zddnscsx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gt2xcyuskwh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gt2xgyehggi.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivderhjp.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2zsphhehj.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gt2tzykdoom.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2pcigixey.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2nwmqwwhy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2yunjvlja.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2htaaywox.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gt2glrwclxt.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gt2vmnehsig.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gt2ercydqhu.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isydncse.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gt2jrxuxodk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvdmmvuq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2jinkwmiw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gt2eayrdvvt.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xzsfwxda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gt2httiqjuy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2zjtutqep.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2bdveaypt.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2kstwtmuw.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2jzredlau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsuenhky.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2cabfulzm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofehhwbo.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xihmphpd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2yunalgud.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2xicikced.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2rmifvrnb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2zwpbmsri.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2xsdozwrs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfjdvfll.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2qowkzkpy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gt2ifiobdrv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2oplvhklm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2rnrytdij.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2fvskaued.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eerecnkx.html


<!-- 参考信息 -->