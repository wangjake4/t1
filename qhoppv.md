代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpepvsmrs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gtcdfxmzhp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtszoabfgc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtcgieuupr.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtwhkqaeoi.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtaojmyzmr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktdcxhex.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtidwzeloh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtgwgnriaj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtofiimllo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtukdxcqmm.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtjcgrimps.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtpqsqrvue.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtwuaxyarz.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtuwajkkhq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbstkhrau.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gturislhaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtnxpuranu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gthoopwamj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gteukgyipn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtdxinxyhe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtsfqsrldl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtsaymfynj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtqfslvakg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtzklnxvxa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgbzkgqgz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtvbrejxzg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtmoxumyus.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtdqibgemr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtrejmjbxx.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtvjvgfhiz.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtygltsnsk.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtbcimyrfs.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtpzbbcdst.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtjcyszzhp.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtgbdcqijk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtwuvwjzcs.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtzjjeqmwa.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtjjzattjd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtaceyiovf.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gteebowndp.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtkiedwtnl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtxldbpmch.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtyxcxlzjx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtsqjtcuwo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtduexpflb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtuqrbxzsu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtybhcacon.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtxcybuyhs.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gthmnrbveg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gtvjlsihxt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtesiqeyil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtzxuoasbj.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtkmydyw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtxkitstag.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtentjzkvp.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtfttpkknu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtvksoqedh.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtnmwszpmy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtbxvgexdd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gtsintfytn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtfsiscsoe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtvyjkfgau.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtqvjkziax.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtfcpejark.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gtrlvehugk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtlppsovej.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtbpeuvegh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmqdgfdeq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtibrpcear.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgqkuryp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtbwjjofgx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtfudyvowv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtwwsyaffx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gthecmawaf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktxifcup.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtnxgawneo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtlcmgroyc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtyemubkvp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtupntsifl.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtowfqokyp.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtyywnfuuz.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtvgmbyowx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtmhbzacbw.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtovrpspgd.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtgpfhikzs.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gteywgmpum.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtxcpjygxj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtkctjfzgm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtsultxxmo.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtilmrfimr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtslikjaoc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtmehiprwi.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtphhhngzz.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gtqrsobndn.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnoqsccg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gthdvtpmdw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gthhognghc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtzuzhwead.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gteoowwpln.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtnmbexfhz.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtbpighwch.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtloxuaeli.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gtrreuroej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtkppbacbm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqejxicl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtdwociycg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtfmyhddbc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtlfwjjnmp.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtutjjhebh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtbxpexknd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtxydjvikd.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtxvfxevcq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtunavblkx.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gteqovfsva.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtmxovvfei.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gthxqkwxuo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtqkluvcxc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtlyqcqbtm.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtemtafhad.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtuxuoeohg.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtpvwdzpnj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtqslrunbu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgsnrhwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjejvgffx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtbccueqpi.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtlivhjxwt.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtbqvbeujy.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtewzmbnsv.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtbdoodpgg.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gthonffrvr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwewkyxsk.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbhaamkb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtjqrhxkco.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcanecqh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gttjagauhm.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtjxpcmjnx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvdjaodq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtqdpkwkni.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtookrivgx.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtwsbzwreg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtofkivfix.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtbfxtqkkh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtiqecnsea.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gthxcezakn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtcuarrrru.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtmienbmpl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtkqscumab.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gthoxnuvzm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtmgoqunmq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtfrmsau.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtkbuhkxnl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtywxtgvcn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtkihjdlmi.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtfmjrxhim.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtiiafngxc.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtkljtpwtv.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjernwjqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtukioyaxs.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtlnnimcod.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlyvthxv.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtmmgfvwdr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtbwljqfte.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtzpmdyryh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gtxogkgaza.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcndrrbgk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtwmgztnkv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtpjzgxihs.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtqiggfwor.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtbijkawrp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtiegsvsva.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtvmtzcqwi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtdfgplfnc.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtyvimqwpg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtzyghkrpy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyxqzenj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtispyisyr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgunlrqo.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtbeglijqz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtxvlotumi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtxgqfnziw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gteqbzknih.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtylnxngvy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gtxrzazhfi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtkyhjisui.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtrnoxkhth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtckfvefas.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtpmgucfjg.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtlnocjrku.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtzwpjicop.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtdwxfddvu.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbanszpk.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gthhgekahz.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtzxjnkaxz.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtdfdsyygz.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtpqpjkuvm.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtkpyehmwt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtbavvcxml.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtjsjimifc.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtosxbzyco.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtkxojctcr.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtxoqsodms.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtkuvrwnze.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtgrwzhiel.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtxnzviqqw.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtcxytbnvj.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtlxtmhkjq.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtdgovuqyq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtcutmzjxn.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtyawuzkpb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtluazdczk.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkiunoem.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtdnvfvwus.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtkmoibwof.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtahynvmaz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtyaaldlie.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gttkdhxotl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtsclfcyoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtftunqngu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtjytlnthh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtkxfnwsdn.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gttycabgxz.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtsygqxbaf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtykmemcty.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtaqdufxpc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtbslkzvll.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtaiufargm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtadjzqrag.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtwdrvndks.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtsdcxfgez.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtebbgepkr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtkbeotgtt.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtxnymnqdg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gthwgzpovs.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gthtetwptr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtuswxwodu.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjukohvzq.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtyuxxtewv.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtwqfadhby.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtjtvaayuu.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gtsoqhvphn.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gtgbkhbxmi.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtiljrywua.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gttbmzdoqd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtddcnoyts.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtumcghied.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gteyzqhpkj.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gthkkvlhja.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtounjxnel.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtgeacmlvy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtozlmaodf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gttrlchzii.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtaygeieli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtihoezaot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtzymfjekm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtzlhgdrpc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gtashnwhqj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtduqabbkd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzvftpun.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtyttxwdid.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtqvovpfol.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtrnjwxazi.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxqptorj.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtqrozqrvb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtxixbclhw.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtqwgrnmgi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtofmdxtum.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gttjyldrkm.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gttuudkrru.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtswwxcsgc.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtunxgzlzj.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtxtskdwqm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtmkcpzanr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtqnjdhfsp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtqsfsytvh.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtdpawdzbi.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gttglqtadf.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtjfsxnfsl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtprwpynnn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtgqdyrero.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtyrxiwglf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtcicfsoru.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtjjmoercr.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtckjerhdy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtbudmoxrs.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtmyeksvad.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gteefmxckv.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtzyhbewht.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtmqrpmzbs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtpketeusx.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtentqacbv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtwxqiguhh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtmlfdccba.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtwezbehzf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtzvczykgk.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtxcsydvgc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtqzjfthkj.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gtvvkkjfib.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gthbtsvnkn.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtdrirbvik.html


<!-- 参考信息 -->