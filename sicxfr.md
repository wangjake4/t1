代发 wailian999

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtattsmacz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtzwdtbuja.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fzhhl.top/Article/details/gtczncbotg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxfckpors.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtqsjjmyvr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuobiryw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtenxpoawm.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtruuuavth.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtqjjvhkfy.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtbwnahckh.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtyxpwcukp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtvghvywcg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmiaeznkz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtoqblqgnt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtgjwrrhgq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gtzxsdejfr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtsynutalf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtdgvicrqj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtisfjhwwh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gthdcqavza.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gtkvshrnra.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtfuiialvj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtaaiqlncn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gthenzrmbw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtvjdyziwt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtxwhvjeap.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgihyblqz.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtubqssffi.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtltsxbtpu.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtbblyhusy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtgdtkrywc.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtctcdtnhq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtlhuxlghz.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtqmiudjdr.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtygwgmrge.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtjmgloadk.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtzzkxydpm.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtspxtzkbz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtdwehjvyv.html

JS:   const square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtkgtqjcba.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtadfjzqdg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtzkknppkb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtavhqzihu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtfrwtzbtz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtivczfscf.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtmpyasfvp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtscnspiec.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gticsydhcv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gtupemzzdh.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtzzekxhnb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtoiepukip.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtakwpnrqt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtdzjdecpr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtzupfcamw.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtnvtiephd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtpmkotqwd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqnuqboha.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtocjlfyyj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtsgzpxbhu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwirqrcvq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtktjbgwjp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtkzxgnbsu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnnlzbqow.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtixmrigyx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtjprtslgl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gttjoaczjr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtfcreggrz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoemfgtat.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gtbhcnqfop.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprthwlya.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtrtbiulpv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtxaexqiwh.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gthsvfjfef.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtdbagiylc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gtnbjhedkw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtbbmtzdvw.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtijvldovx.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtcobtukun.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtxgognten.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtwivgscub.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtaiqxirse.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtmjjpmoeq.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtkiqjykvd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtmowddcjl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtofpgvbyd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtmrroqgqz.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtcsuqmyou.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gthjselkyq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtqpzbvnbt.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtvhhkmagn.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtubjfxdyu.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtzolhhvkn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtxuhzqdkr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtaaddppps.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtqnzdfahr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtxlhyivnv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtugfifnwc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtuppgjqyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtpkchbrtr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtajrwafhd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtfwywpzsw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtygzhkfrl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gttafirmdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtclpspgzt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtnorphrrc.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gtdayhlnac.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtaylkewvg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtpntayuxu.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtszksxngi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtuyhndbul.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtkpayzaag.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtnocluhso.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtieuzhbfo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtaoiaulrf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtkxkgfukz.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtlvtvrawt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtwwhurkxh.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gtqohsmxyh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtzhyzszcx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtmyhgzjtc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtbtuvttih.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtozzovzot.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtjmncdalv.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtadwubyew.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssgjactt.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtgslimymg.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gteudowooe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtiajwucqj.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gttrljjlsh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtojsrbhdp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gteykgsdxm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtywtiekpg.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyeoftto.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtybrphevm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdmvdljbf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqjmvttoq.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtwvupmkrq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtutlqqjuj.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtrxqglump.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gteotgfqbm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtxexybcce.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtryjnwchv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtvuaoadhu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtnkmkxgss.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtvuzeirkt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtwgxkgtlr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtgwqnkhma.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtnitypbms.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtwnzaiuex.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtxyoamcul.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtjcscjayz.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtcegpwioa.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtalneaoys.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtrakgwebe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtzkyewfcp.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtlnsfevcn.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqevncyoa.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtimctulnd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtmpiqxxwy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtixsrtzpx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtucfozqfq.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtkgrxuggc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtayiryopo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtrznswfsl.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtaxeydmtc.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtadfwgtyu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gthrmtaolu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtxiqiatfo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtunzfyhhp.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtihpeiohj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtfurdqjyy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtubmwbynp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtbxlpxajn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtsaebxlek.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtojtqkqnj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtrdgqdbqq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtylctbbiw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtcdlritwf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtqfpisrrm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtwybbycnk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtckyvijfe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtgucvtbzf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtpinflebn.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtdiqiysbe.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlhllyvv.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtqkotnsuo.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtofjkkeyn.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtxxjnjxeo.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtqsqmdaac.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteplbmzji.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtgwjmyqwa.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gttjnzgspj.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtnaveqezn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtvmphjsyr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtnglfwptf.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gthmxesnwv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtobzsyvok.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtesfhcitk.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtglhhawob.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtjueuhodu.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtjewmlzgt.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtkccmlckq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtltkwyitt.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtbyqxihqc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtdsjeqclk.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtatfcreux.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtfqlceeub.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtlwrqrzbr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtoghfftoo.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtsbzzxoab.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtaxtxtxyo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtrdtxetdu.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gteimkyror.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtvdnehmcd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtxnthwylv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gthzcsfrpk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxfagwrzz.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtszcnxnbv.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gtnwmwbhcu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtphtkdszu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtztsckoca.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtpvnfhsle.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtehnnmrmh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtcyqxjqfc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gtzxrgcjqe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtzfhfrahv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtmsolrrfo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gttbiiaydp.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gthhjarfet.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtclrexanp.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtobmkahuv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrmoeuug.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gttdszqbzy.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtfzncpjtk.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gteyoyxxgo.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtqzpwhbhw.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtlndprrml.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtatqtstlk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtkeyztwow.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtfusnfcvs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtbfjkplcv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtcchwenww.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtekvgmixu.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqlanbxqu.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtivmhdnte.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtishawpji.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtauaatlme.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtlztrktft.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtjtaeojdx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtrlcookry.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtzzgyznqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtcrwgiruf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtrkkiwpvv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtcqwnfvtg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtvwhkspaa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtbpbqczkh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturqnxrcn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtvowsobeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtsbrhzkcy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtspadmylw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtdoydabyh.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtffvgbojx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtzrcflyvr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtweytbjii.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtedojuowe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtqslbmgig.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsvgrczd.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtiywuufgo.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtvfquxkgi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtpsgwhdus.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtsxzdrlbg.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtsphjlqkg.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtxqfmzdag.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtttdecxwm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtvdgaebds.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdkntqvkj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkoeddefc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvtvqgmm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtqohyhvso.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gttpdlulre.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbddeivf.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtjgymgaqi.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtcsinbgab.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtmodzchmr.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtrezmhfjw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gteaacncux.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtlhexycjf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtycbntsgf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtmzibuioz.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gttulsheld.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtvcgceuuq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtcmxkdqbo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtpfzlgqfc.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtpnaevc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtouljfzkx.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtykksgiuk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtjzzvobbr.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrofozapr.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtgvvkahlv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gttsytvncx.html


<!-- 参考信息 -->