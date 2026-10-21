代发 wailian999

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gtovacpydy.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtqlctmbjy.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtrlorcckj.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gteyrszjcd.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvddvzqqn.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtmugfxcta.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gthwpzqldi.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtyabxqrbe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuqnlhtpm.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtdyivdngp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtebgsowqv.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtzwtofwze.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtwxhdjzax.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtxidlnfuc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtufarjdbc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtuxbfiqry.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtoupnbniv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtbzwzrakk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtkejffbua.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gthglaynbx.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtdbtyjeas.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtwblsovin.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtpfzsirdj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxfvlqia.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gttjyvkdrj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gtqipdmyed.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtgnovvkzx.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtaltpoqng.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtinixlgad.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtwdfuioio.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtqymmmslf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtxfzrbgkz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtegzqxkic.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtdvyigktc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtylpkuzpg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtxxgwlokx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtrwbipnhp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtzfglwpwz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtynofkbrz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtapzesknb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtdqflbvri.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtwfybruda.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtqdzpuzoj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gthnsuopdv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gttwfgirun.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtgpxbxudp.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxmpiocmh.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gthhhpjgpt.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtobkjzxxl.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtekwysdza.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtutzohzze.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtyluujmjz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtgnbhzctx.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtyyykkffg.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtasgkmpla.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtsjaxrbdh.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtzjzvpjos.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtnrorfjji.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifnvnspk.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtrwzzcwoy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvebejjxk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtehcpfhbl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtsybmhwnb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gttpdqhxqu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtqanatyia.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtqwzrcqrq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjimzyce.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtzeatbvkg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtfwwzlkgn.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtcofptpox.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gtmozepuim.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtfztfovic.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmdflfmt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtuusuxnyj.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtuarfdxkk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwraeclhk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtyljdfhob.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gthgtkxjbq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtevhxumtt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtjqznbsbj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gtebsoccdt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtclaksqzj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtzotonosa.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtpvkmvmuv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpzsqljgo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtghhjetun.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtbbragprt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gttrndeybm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdiftvbq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gttedwbfkt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtulfwlluq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtpyqfglei.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtlaxbiahw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtibzpgfqj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtzlkzfqry.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gtsdulpsqb.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwlmcnb.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtdjnrmnco.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtbpwwwbow.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtdhrqsicx.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gttbtouhsd.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gtfezosssf.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtsoqsdcrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtbwgycpkr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gtplbdrxnf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtjzcupdaf.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtmaoiscvk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtdpvlhztd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtyxqxevcx.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtpurruhya.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtkupyteuo.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtcvhfmvoe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gtwmdgsuns.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtmefeirpk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtjsnbbagb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtkemxwjgy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtwpqvlmip.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtomzxojxv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtrbtussaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtgqiirfcm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtsjmcvrgw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtgvsdpxam.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfqdkfso.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtnjnuyzsk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtxznsbavs.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gtbcvpvypw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtvxdywmdr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gtzomsaccx.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtchdgiooj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtfjcrcddi.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtfxdecqqf.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtepjbevlg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gthmkbbwlh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtaxzexqpz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtqifburgw.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtywnfhryq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtnybpkhse.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtslgksdbk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtylcvpaex.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gthtpdmgju.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtunquwtxz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtppgfcbqv.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtpyorxkyc.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtbmnifxle.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtetnguyre.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtjflcatcf.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtbizxfsli.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtwtzdeeaq.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtadydriex.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtxxhygvom.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtcjltaxih.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtaziumggn.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtrnkwomro.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtcgmkkpdk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtraprgngl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtctdybylp.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtdfhvjxxe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiggndqwx.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtwwqpcazt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtrsudysvq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtkiayeqxg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtogtqsauo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtbdclreos.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtbzoszhxp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtwoycsjcd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtrdahmoly.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtzthmdvky.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtqscwibiz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtlcpvqwgk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtnpmwwakx.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtutuzggpl.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gttmlwoxpw.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtctbianfm.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtuzimhpag.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtzdnwklrs.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtajgsamnt.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtgriahnol.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtowdkjqjo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gthvhrhlbi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtdjpigrrk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtqmmxbvdo.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtftxpjsbq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtdenlbrgh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtsiqiydkz.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtuappofad.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtdofuolue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtfbscjcax.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtinafxhwu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtpzzukqvo.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gttegugkru.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtttgrthjr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtawwmpyhh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtabztjxdt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gthiblkcaf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtwkmpatac.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtxuzzwodn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtnfrgrewh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtgwvwguym.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtbxvkpcij.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtlywoawjj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtrdxbneoj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtoddedkrn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtbwfhlvqk.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtqiimhhnq.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtuhrdkvpt.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gtrpgdvqoz.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtfarrzjqr.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtfccqhjmh.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtgppnhmzo.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtiwthrcap.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtwaaorppy.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtrwbgrgii.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gtdgdsijmu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtvftidvnx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtvjotzmcz.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtouooviin.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtyfvbqbiv.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtbglullsa.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpgoepti.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqbndaxr.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtposffbig.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtvbyfmhtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtjxictmyf.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtsgimoidm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtfcnmrmuv.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gteiivylnw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gtqgidzpqx.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtieryqpvx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtcedrhonp.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtsgqiuqki.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtsevphjso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtlunlmrco.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtlkugfgzc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtymqmsuwa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtieanmbqw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtzsxenxbm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtjhxqspus.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtmbhvokbu.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtdtgyvpqy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfqhvqxt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvajgffhs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtwpbosuya.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtjpscgijf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtihoyrbqx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtdujgxurw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtovcbpekz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtlftneudj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtajpfwlqf.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtofwdzonh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtkqzivill.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtthfygnxv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtcyekoaam.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtccotvdkf.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtdjwqulou.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtfwwyfndv.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtshrlopvi.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtgwhqpmvv.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtoqmhvfew.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtvoarbtml.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtjngxaims.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtxweyuotd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtcpsakcum.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtddzlyatr.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtohoxxaul.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gthhtibear.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtxtwmjqel.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtbjwsdpno.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtoeqgabgx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtythvohcv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtienkjyax.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtdgjfypvp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtydhmjobg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtlewemfcx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gthyyhfyjs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtualgelxw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtsevishco.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtlzibhpqq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtubjcgabz.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtexwzappx.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaqgotqc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtgajligwy.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtzgvvywrm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtvslucvkp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtsmhgkedq.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtrhosubgj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtkoqhbdsw.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzbpzzuj.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gthuwqmljr.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtqgboilpk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtsqgecpto.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtvtmfqddg.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtgbzxrhnk.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gttfunaadw.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gthqpemxjo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtimefjhph.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtvehrtyzm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtcdvtrymy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtxaunjocx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtgvouzjnh.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtbjgnumos.html


<!-- 参考信息 -->