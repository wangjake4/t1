代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtefbreytt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtawcxndtc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gtgfaryfju.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtavdlqpwp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtkibsmhkw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkyjhpkx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gttcpxorbv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtqrarxxth.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtzmeqsand.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtibhmelqw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtpdcocgzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtoqhwuzwa.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtyzccfery.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtkghejwnf.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjsacphzo.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtvyowzgnu.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtvxwidyxb.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqsflvac.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtzcuament.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtdexjdwts.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtwxndokfw.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtqvkpiacy.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gttkjjhjhc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtjnhggdne.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtkldsuuiz.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gtuplzvztn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtochukvur.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtbckurwfs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtozjcasms.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtktdbuoyi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtsfjidijw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtbburmdql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtyxvrbtfq.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtgpkduquf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtzkgxwezm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gtqiepbzbc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdnihiyt.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gtasmzyikq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gtqvejophz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtxslfdyao.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtcxwxawvf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jyoumei.cn/Article/details/gtorfpuqdd.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gttpdsejmv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkurmeyt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtdecijzib.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtjbzexwkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtuuxyvghp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtovdkohaq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtolfkmdip.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtazaaalpl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtyqsmgcsx.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtvkqnowav.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtzciczqlf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtqmhodrhz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtoxoxlrtr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtziglrinf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtqoxhuzel.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtdwjkntgz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtbzevzupc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gthbrnfboz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtlsqeafvl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtdjsqtrox.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtpznbnokm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtiizlpzpc.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtjfeayvde.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtfraeetzv.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghvdyngo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtwyuhgeci.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtgmqbkxgh.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtjxygroqi.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvokcpgd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gtdaeaskot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gttwoyxvha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtoefjhhyj.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtchtzrkjl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gtyxahvnuy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtxymruscc.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtpjmmtcos.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gteukkwtyh.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gtlbewqiht.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtvgmnhmzd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtsxkitazd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtcfelnvpj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtpeokxtng.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtqolxbisl.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtumkvcmls.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtvzmynihp.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtzfhvaedz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtilpcxjvs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtwnqcxdvm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtwdlyngdo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gthcsxfdue.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtuhagrujb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtxmjvohcq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtquposcng.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtktoxmtkg.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtblrbqaki.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gteywbjgsm.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtctxkbqwk.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtghpibqpz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gttuqjopca.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtzannwbsx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gteorbmgcs.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtnojyhkts.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtranmtgud.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtxlibjfdt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtovrzgvlu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtedlauvpv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gttuhuymro.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtclpftbsh.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtmkfszlgb.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtxoswuyih.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtohchxwrh.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtwhkvtddv.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtzzibfmmg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtsbikjnyw.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtglkuhqzr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtzualochx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtaxqrvizm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtjivumgmn.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtoaoeyibw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gthzpcntwr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrkzizqqt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzwqyvhi.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtcdrnvkfo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttrljovwp.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtjkjkgnvt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtgkfupexs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtumliwpru.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtxztodbxf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtudltnjri.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtsibwjwyf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtexvqnhcs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtvtljnjtf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gtmwjsrmfl.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gteesteixz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gthvptxsqr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtidrtryzf.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtalmhjhzm.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtyalhksvi.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtzwqivpsc.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtcqrixqwk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gthgabhgox.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtztawnlmz.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtjdmpdmef.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtaajsqkan.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtrlowufps.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtlfkujktj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtqocbpcjx.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtlikecsfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtnfazbikr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtadafymlp.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtzwqlrfvv.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtmorsalxl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtvtqpyjoe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmohpletd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtoyyazrxo.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gthsbhwztc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtpnhqfzmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcpxidoc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gtzachfyzs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtyzxjvxsc.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtvsvymgth.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtccayasip.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtkoqpwfdp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtewdcqmhy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtlaclznqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtlwwxeqbi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtknoplrhf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtxlemdcon.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiigroqph.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtikrcfyxf.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gttwexwrkj.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtokcbuwsx.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtrvposfcy.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtuqrkiihh.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtyfctvqqy.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbnwmfjfb.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtyklzonjj.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtmsdjdqvi.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtyxstwhgw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtaupxkvwj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtxurzypxb.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtvwofzijy.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtnzqoonay.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtnbxeiwuv.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtwudmcrbm.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtapcbihfh.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtjwiguoib.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gtdhdkfsvj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtxwlscifz.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdcxgipi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtioonkcqs.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtbnycujdb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgrjtfjtc.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gtbcsrryxx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtwpqkdsts.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtuvpguhzs.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtqvmbrfat.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtcjxzpnmn.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtzwnatgiq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtsiwmmrhl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtjcovmika.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtudzeknkw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gttambhuiz.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtcsiwtyrd.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtnuprmsdx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtxpfomjvh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtutkfnvws.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtyjhkfqqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtrxogbdac.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtnlpuampn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxhyrfei.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtgkoceutd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbtjsazf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtaeijzqff.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtwntqmyef.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtezqofrml.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtlplprchm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtatfixero.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstmdfcfw.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtvprqshad.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtgbmnqdbn.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtwqptvujs.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtwqrrxijn.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtozhfpazl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gthxmkbbvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gtgxizmtva.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gttbgcvlob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtpdfgcbaq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtbdktnolj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtapqlkooj.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtggakrcxe.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteficsixq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexyqnabo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gthfjnlkmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrzvrzka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtppnixqec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtbbibmodl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtafvcryrq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtgwvrfpzk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtiqqfiwhl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gthgkyqdhz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtggupsmmw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtutfgciwy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttexbcusp.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtskrpcyfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtgpazrwpm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtgrlqreqw.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtfosqzpsk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtaimoulsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfulbwurx.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeymoltk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtbsnjpomk.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtzhwpsrxe.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtpzgsznwv.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtmrxuuhbo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtfeyszots.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfdfihxu.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gttokjxzpy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtttjjpszv.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gticomvfxi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtilkjwfwm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtubfazocq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtqrrgsrgx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtmvxvtwvs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gthqgpzpah.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtxavznaor.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtkjnrnlsh.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtkkmwxcvq.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtghlhjhuz.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtrxbyhwzt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtmxbunwdl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtuwbrvllq.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtnytskjbn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gttwhqjmmu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtumjzyhxu.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtnnlrqhkq.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtawfvfckx.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtoeicuvpz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtqwbahpor.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqojkdlna.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtiepjhxxh.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaltqgpu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtiwjwpkwa.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtefuwdmsu.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtkhnuylzo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtscqqilpt.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtinvbdrqs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtfnjooeuj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtvxpdpugk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtgjnheeej.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtgqykozew.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gttszwzltg.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtslqiaflo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtchdesuur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtncpvtwju.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtomodaajr.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvupzyqoj.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtanxxughl.html


<!-- 参考信息 -->