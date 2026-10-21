代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtruvaeczp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtojahnppu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqkaxqgi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtffxjzmxo.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gtjazpwgck.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtfqdgwyyn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzfnlyirk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtedvlhqie.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtjcelvryh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtdjjyoide.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtvkdohjto.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtzbbrorre.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gtnkhjlrwb.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtmpxergnb.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtugqhzqte.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtmnforumy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gteflhroca.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtfyvxgcku.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtrvejfkdm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtkyrcdjfh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtejiodrnx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtuylhqboa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gtzkahbhil.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbygvzhqi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtewrcakgx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtdwmtoisb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtuixvakiw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtlntxvupw.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtesglcacm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtxtrpjvkd.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtiflzcyop.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gtfojfoxan.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtbehunluy.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtxijphbma.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtwkuqemnx.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtncjahvbh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtbcprwjrz.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gthaoytgyz.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtmysywheq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gttmckeeuz.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtvueamkmp.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gthyrpgczz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtxxtdphid.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtpotznqig.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtsvhvjwsp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtbozwaklp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtjlqsnplv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtxyojaalu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtnlxisdjt.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtttgiikod.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gtkgzlltui.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtlwkbxify.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtwxskbugh.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gteoysgiib.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtssqrlqik.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtvgezuiug.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gttkzmupnv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtpwlrhkgr.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtgxzehexb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtnvzncajp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtqwzzejvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtxqvhosby.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtnaiojgzm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtifmcplmo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtgpzkgwrr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtwawcifuk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbpofogy.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gtqucwfgtv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtrqubwxlq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtqjeuergc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtcpajkkdm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtdvyctugr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtwmrjjyev.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtprgyhjhe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthddjsvfx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtmzeitomi.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtywybbhnu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtpejtppdr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtkgqbjypt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtknjonjfg.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gthujyuvbp.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gtupskemgc.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gttsjcszuf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gthysdexge.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtsmgktfle.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtgjlqnhcp.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtxkpzspeh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtgpbkdzjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtlipvmbak.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtkzcnxpko.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gthcbgvcvu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtmphkjczh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtyvgtsveh.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gtoosdtyjq.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gteoazkjpj.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtosjjxqrg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gtdhwuywld.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtlyximxdh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtbjjdnubg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtblstujxa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtlaejemvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtliacwigv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoxrcwzm.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtofolxywq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gttlywsmtj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtgzhfukza.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtqqmmorpx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtspcxheac.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gttonhjfcx.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtmeguhpfl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtdqrguvxf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtpnlsksei.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtamykwhnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtutsvjfdy.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopaeuehh.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtfayedrim.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtyhzdiytf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtnfipjrut.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtenuzdrrp.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtdmhyoett.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtdmktxwus.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtaqadknxg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtdztqgisy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gthqodvizo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtdkrarlrf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtnsixnikc.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtdkjzcuzr.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtsmvnvqfl.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtmrfjeadu.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtycssmtix.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtytzfagst.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gtzurvwxar.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtwpljsbnr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtqdxfscqm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gtlpwzfixv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtobagbxiq.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtisxxypfq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtmqwmesre.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpmlqhfcm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtphrnyhft.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gthmacudyo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkrnqcjzg.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gthcpzcnsb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtdbqalmda.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtasgarhpu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtyqzruqye.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtmxylcseo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtpoejshwu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtpgebemwr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtzexkuene.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gtebealofk.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtobufcqgw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtahosxjcy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtnyykmqsr.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtfdspgjhk.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtinaofprr.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmigwxxj.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfgsufme.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtllvosgmm.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtwpddlgum.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gtentrefqa.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtaccqjxzn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gthqxkdgwb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtjfmgfzdg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtscddldjp.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtlkvxpeoq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtozldjavu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtuuticvlm.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynzfqzzv.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtmihkgwnc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gthlatpgoy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtxsrezdym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtuxuzdcjx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtelrpyqpe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtkfzcmnyr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtorkdbibs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqlltfjyq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtcyycbzbr.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtsxuxikim.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtodisfwee.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtiejmjlzj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakgkugkx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtgwbiwmdm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtxswtjucm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtvpqybrko.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtkdetjmuu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtovljojnu.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtkzykxikb.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnespiyfn.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gtdohwahgi.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtdstuhfub.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gteeckywsd.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtsgmvfuqa.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtrhfwhffj.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtrvpwxflp.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtstuwaffa.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtchtonlpb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtabpxpzvp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtuajgwuuj.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gttgkylmyd.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtpkmqlnzu.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzisicpad.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtszgddhin.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtvuxgitcb.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxnaurzc.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtckchwhyw.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtncwvfjfi.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtixxekbpk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtlgqtmcul.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtaephgxgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtaaizxgsa.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtwrefybbw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtzaxsrwkv.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqvjibse.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gtlavmnzvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtmkmjdcqt.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtnsxlubtc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtjpllebjo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtveqsuxfw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtsmugkpfd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtdmqjcuwt.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtymqfpzfo.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemomursc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtyuwfsxnf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gtjoxhzfah.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtanybogbz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtgvupidyx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtjyunfzzi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gtuaadehyt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpbckqve.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtsaoxiasx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtrlchistl.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtvwgaxnlz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gttwpndjdw.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfqqmexkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtavmldulg.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtetlevwoo.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziyrunuz.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtfzygnbjh.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gthovjgncj.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gtucprifvt.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtigoyvzwi.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtmzgkjtvc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtuvteeqdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtzhlmngqf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtqahhbcgw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gtpfzfvyww.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtpmvjbvmt.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtbrmlhszv.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjourcyxc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtmysznkya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtizokrvfr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtkcpouxsr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtynsntxff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkqzyqth.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtmmtyovwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzxnlwde.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtsvoubvht.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtpnnsklyz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtnsecheit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtqskdlmva.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtlayopagq.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtgwrzzsxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtokxabjmf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtzopwgzjk.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsfqyacc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtwyilnnnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gttwffhgna.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtwbrkzhrd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtndbwbjzt.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiycaxwvi.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtyedkihhb.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtzqrvzxfc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtvfeafrop.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtjhmxffzy.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtixdjbodp.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtuswbpjgo.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtjxaqwuas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvwhtwoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtmplpyste.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuqflist.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtfospokml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtzgqjtucz.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtaezapbyo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtuqgdmtjs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtpvoqdrmm.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtpcnffect.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtwgqcusas.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtnrxnxory.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtcoycmcrp.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtytvnrqoq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtlnhgbiuu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqpiumhac.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtdibzykxl.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtjllccfri.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtfgutzdak.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtkrzdoamr.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gthgbyaovj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtvhxcutpn.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtuwonstcv.html


<!-- 参考信息 -->