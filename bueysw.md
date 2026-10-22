代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhwbnygf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtbuankduk.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtyeoweriv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtvlubosqq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtlwhibsoz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtdrlwbzad.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtpfnxewtp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtvduapkbu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtfkbnlbuw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtehuwmfjj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gticqwkump.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtemyhfebh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gttdpafthf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnixmtshj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtdqwodaea.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtunzbuxnq.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtxsgoevgz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtkdjwdpir.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtlriysruw.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtcpgwrzvd.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtjbkonwkf.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtesqwvxtp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtjyziqbgg.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtpuyroikp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtrggzbrkd.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtpylmhhvb.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtkivnqtiv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtcqzxbbir.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtamrsjkyr.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtvpxjmosq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtalcldfah.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmadrhfqu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtbpfvufuh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtcysckekm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtynmbwamg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtycwwghbe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtqhvpjtrf.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtlcecqeds.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtqeyglnlw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtztzzfhdj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtrpslgimr.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtmrlyvnsw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtihjvtlue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtoshcwflu.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gtkkdunply.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtkywtczsf.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtipqjmloh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtpbapbpgg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaimeysg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqebweres.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtbarvwngu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtamadwivs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtkpinbcrl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtvuphfhgw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtzccfxakr.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtfpaietuu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtqcpjtfnv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavgxpyze.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gttzewpinp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtyizepnjf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtveuygjlc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtflntaust.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtgxyqwgnw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtlrsistlp.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtbnvyayto.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtkcneymtm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtkrvbkxwe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtoxsfgwzn.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtgutbqqlg.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtyldlxzdg.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gthlhryxfm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtdfknvfhx.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtsptbunlh.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxnkpcye.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gttnwartpp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtylsoplfr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtzikutytu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtqhcvcmes.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtyptqabfo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsstmvhw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtpdicuqow.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtipoekjah.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtpvzaqwus.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtbypmqgag.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtvvjbriby.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gttztzqmad.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtewroxgjm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmlbjsvt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtxvzwzizx.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gttoauehpj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtutyklkkp.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtyfwewzuy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtbplgtuig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtjxaiaxbd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvovenlxb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtwvqaoy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaqnbejg.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtidgyplfk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtxehjiftw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtnytmsuui.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtccaxxqzl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gthmjddcmv.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtbmnaqovx.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgxbysvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtjxuffdqy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtrqhbclkw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gtrlqvdqmd.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtgzrpfdvd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklhjykdd.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtrslavzeh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtdondwrot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtrezncmfr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtumjtubfn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtpepsbzzf.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtaeiujezw.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gttvjpgcdb.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtxmuvirni.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtvqdrhezb.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtvccgtldi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtafndotoy.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtswrjgtaw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtxpcvgtvo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtubawpxzf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpibxkbjc.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtdhwsrocj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtbgjzmywp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gteztevjdz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtidxmcoht.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtdlbsagjp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdywoudje.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtasbujomx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtzcxzzsxx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtybppsfeo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gthkjswcah.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtlfmgeysy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtlahqurbd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmhxvvce.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtsduvxhvq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtyafjmlkf.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtmvkmrsyc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtnbrpsawf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtrxfistxz.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtfouvgdxv.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyvfzzvu.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtmcqmkrmd.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtoddxjpvu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtxxuhlsze.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtfdeorrhv.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtkxuxfboq.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtfiltthjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtgoqhwhak.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtahluxqdz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtzhcpkkar.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtnhbqslxq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtabcmtzmm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtizluafnb.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtfmzookiz.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtszcomysh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkuhtitb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkwtslzlh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtrzjyzqsn.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtriavnaib.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtgjsmbtqi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtqdzihzrb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtetlfqqph.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtxshtndpq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtuoorlgrh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gthdfzunyi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gteidhvydv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gttpaqebmb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gthrbzjbmp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gtlynupovb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtiovqnqkm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtxyxiuxxf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtrlotbdhl.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtgtwcmhqn.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqvwbuim.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpgjelsl.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtwdwqbljc.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtuzweuodw.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtpicbwvjk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttlbliijb.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtpvqcbmaw.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtenlehajs.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gtexdnkzmq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtyiwwlqqr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtqyovsevv.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtrclcbljv.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtunnyuchz.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtkahuixyy.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtlguklnuc.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglpuukda.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtjfvmaezu.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtndqtpeob.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdyifkbx.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtswrsqcus.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtjzgdmwdl.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtjjkgudmq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtvlbiuxmv.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gthqmcoroj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtspzllhgq.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtbtijpzob.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtxosynlkk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrhjeffe.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtbfcibcdz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gthfnuwbpa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtnhpxzdyy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gttebllfcq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvlclvxcq.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyysvpee.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtvdfdbbzv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtcnrfadjr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtvucomhyq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtvhaoolgu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtebdjhphw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtoigdqxwy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtporalfnw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gtzryackqu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtypvdmuvw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtobwntoew.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtzypmntmv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtrybuluzt.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtywirlayx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtvfitjebs.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtuqgaiqdc.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtmhrbdbtu.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtqzdsjaur.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtfxfwwytq.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gthqmcvixs.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtdqqsouww.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtradpybwi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtxngmczsm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtdqsznlar.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtdmdbvppy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtqtfmbkbj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtmeyudgwm.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtpiserxgg.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdyiceor.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtlcxbalwa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtmvqukoih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtsughgyag.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtmdvdyvhk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtnqvqxopu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtqxsbuykl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtjmakfmch.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gteyqsopqq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtbagkeuoh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtjhjaawbf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtkfbnfift.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtthhvgnnp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtemdrybge.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtcdofnbvf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gttpulklqr.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gthqxpxpyl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtaikbxuih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtwjdboxht.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtaqzlclfw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtdqbmobov.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtqgucdomy.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtenpnpujk.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtnescfezk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtqhvsdizx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtekuakvex.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtafjqzyvi.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvfzzkfii.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtezdrhkus.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gthokrqvbg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlcxnglks.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gthxnddetp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtxeaupubu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtmrxcfqbg.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtmrmmkawu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtoroitwgq.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtvdkrnnsq.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtiwvrzghr.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtoiljhtsz.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtiajooods.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtgvfwxrod.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtfkeegsqe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtgfgxmlmi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtxsceswmh.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtdgpejpuz.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtcniiqifx.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gthphtzxwg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtrprbtcgd.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtudunoefr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtbohbpftx.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtagmrexhz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtyrjaginc.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtuapssluv.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtclrosgdu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtbmwgbvik.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtsinfaqrx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtksjzfggy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtkzvvhvkf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtaimdinxd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtacypismw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtyryzyjkn.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtiyuhsuyv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtnfwpdhzu.html


<!-- 参考信息 -->