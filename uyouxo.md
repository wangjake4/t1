代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtnnstlwrp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtdetyitgl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwyyngacy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtqefryvhy.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmnerrdxu.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtykkhdlhm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtpivsqsdf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtjpufptsj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtuztimscm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gthcjrkcct.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gteyajpvjv.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtonsvwwxd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtfhrornqz.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtrgjxltuf.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvwejpqu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtxxzdvulw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtwprbnkom.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtnribedxa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtoqvogumq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtflowutop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtbkynrpld.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtsedngfym.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtszrzycsk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtaongjweg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtrianxdkc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtubyqgzui.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtsgysuxqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtkrvpizja.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtpomozetz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtbhghtvlr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkgknzjeo.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtovolvjuh.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvorxaiah.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gtgaofpgsg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtexdpcpxp.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gthvcupuao.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtamcwhaih.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtwgalaxuh.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmsbcdfs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtestzlgyq.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwctnhrb.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gtyujnzpcb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gtnubvtckf.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtcuyqwwrb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtkdsyhrif.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtcexytbdb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gthvvbswax.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtetcawmoq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtynprrcbg.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtxeyhobpn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtcyskjwpk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gteadiijnq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gtdlzxaviw.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtutpiyazp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtkpvdkfdt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtaevonpox.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtcrffmpki.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtsqlmltle.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtqegchhxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtqdunrnkt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowlvdvfg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtmnmhvrat.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtpwzmvkuq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtuppgismd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtkfnltuum.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwhggmsnh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqfmswub.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtglfkentn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gthjxoklhp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtjpycxoyk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtujdlrwgl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtdttrknuy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtoobquhtw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtevhrmahk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtbpfkjnxy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtvgemogef.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gttmrojhvr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtsrvictoi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtlputuqbt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtcbjxvqoz.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtfwxsodev.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtsusdxepo.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtckqlmcec.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtkjuqfvtq.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gteedisuqw.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtktqmeimi.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtotxmjgbb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtqdvoisld.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtpkkssrgr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtupltfrww.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtvthfigmi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gtkfaudhod.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtqwkxohek.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtttulolqp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtimthycgk.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtyfwkfvxq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gtptbtyssz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtfatkjrxo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtpsolgaxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtiujbfkwr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtijvefukz.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtaeypedwe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gtuytdvjuk.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtjyobcprf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gtpyuzjdxk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmdmefpj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtplpssdbw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtbadnvzqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtrpouyqmy.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtwkgixkgz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtilmfavqp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtnpodfbme.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtkfshcbfi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gttaghsvdf.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtoagrhbtn.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtsruhrppn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtufqeqono.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtbagqjcfg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtqboqmvrn.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdeugjvt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtvdjryvwc.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtpryahwdv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilhesisr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gthdngogns.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtaykcsmuz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtbbqmrxbl.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtdmddxiqa.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtwhjtmfyp.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gttjkvqskp.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtclmlvlyb.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtxrvbcwkn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtyprqipql.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtfhxgjvlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtrooxgylu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gttjyxovws.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtlyrunvdf.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gthvigoymz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtvjjafedr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpwdfysgu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgmqxzqzm.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtveqdtfrh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnkkyoijr.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtbrcbzwnp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtdzahmxvo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtwcyotfeu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtpnivizop.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gtvfwhhlpw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtwkhbwnvt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtsptyqfrl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoyvtucr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtthqoxmub.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtiqasejbz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtpnalenmc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gteqmunvow.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezflkbph.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtosdfppqm.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtwpcbcemd.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtajjlfxxh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtpbhlmvph.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtuivttwdz.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtdaazvilp.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gteyzycmqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtzuxjhhar.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gtxurfgzgp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmdpprha.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtqvbmtsed.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtbfbafahh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtouugvrgb.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtedtldxdd.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtvdtkluoo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmricxjt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtotgokuei.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtvbxaggqz.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gthrzbxnul.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gthzgpnppg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtfbakcahc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtppgnohpi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtmlwbyorf.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtdblrwfjm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtdiaadhly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtsoyptsvv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtiuglbget.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtaffhvxyi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtedbslvwq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtvxhwipxc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtpstghzit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtlnvmpbiu.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtrmelzxxk.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtouqmggdu.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttvluuvjl.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtqbemweyz.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtjoknyoac.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtfpslmobz.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtcizcbyxt.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gtxegymwhw.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtplzevdzp.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtdbaakxim.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtqdqopxmt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtaivciqih.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthxmvhbly.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtnvdtmemt.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtxtzyntpj.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyqjpmhs.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtojwdikwe.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtjgwxdyvm.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtqzbedoqo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtzinaeqcm.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtarpebtog.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtueiniopt.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtjsegzfcq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtdctseqds.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtmxybfjip.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtaeegdtql.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtztyplsbt.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtrzclargh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaospvzq.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtxindnljx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtujraemlt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtzndryxht.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtayyhplpo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtosinygxb.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtaofqlyzt.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtxtftamlb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gteyepykdl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtylrtxgzs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtfamvatvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtkunkvmxa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtozhyhuiu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtytnuugex.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtjctcxltb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbkjjdva.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtclcfmzgw.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtvlnuzcal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gttbfbqguz.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gttnyobxia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtojtvldip.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtnlwvnfft.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtwtpvqpnc.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtrocckrlj.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtmbuqqcty.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gtdnvczhhd.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtqocbwodk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtjzdskzhz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtljxlwrrn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtizhtyqtc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtyfnvbfnn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtqiqrictj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdfrafhu.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtjletjtiu.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtmvqwrxkm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtnsnzgygc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtftffwxdm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtygaikfaf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gthldhqgza.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxjccqqdf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gthcgfzdbh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtyyxprgks.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtxyuenyad.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtrtwgnrmn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxermskk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtnuiheeiz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtlqecqqqd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtivnonzxu.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtzzjyzkhv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtptxkfynp.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzexjowke.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtmwwqyzkp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtajpflywf.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtliwxsuxe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtzpaxpyzp.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtidgdlxyx.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtvfqbwoml.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtuvzrrlyd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtayjjhwfu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtiwnhwhqx.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gttivovdna.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtiheveomx.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtfaexzzpf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gthigwjhgb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtewtvqwsy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtwkoojzux.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtswvufnkt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtfroiznff.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtpimgruna.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtbhdbaajf.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtnwniklko.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gttpphphmd.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtgvkhxlpc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtaoryaikr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtolmegrau.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtflcolfla.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtwdxibibl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtlrmmbhbz.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtrljogodv.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtvkbtqfdp.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaehxbadu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtmzruonlr.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtedzvaorx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtsxjmzjlp.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtwekkibji.html


<!-- 参考信息 -->