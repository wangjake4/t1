代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtsuekwbyg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtuqulessf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtrzuoyzmb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gthpneajja.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtgozwvhbv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtrmtaonze.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gttfnfjefg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtokghbubh.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtxechqiaa.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteinirpeo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gtuiavuwot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gthhoeeswo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtyifczkmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gtmwofpiab.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gtwwqdcwpu.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gthdjwlybd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtpwohvzju.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtcithmgok.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtrjqnyikv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtfigaljzz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtvkxnenke.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtiktijpos.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gtdgklecla.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gtoshywbdv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtpglcujfc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtwisizhwc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtncgwijvu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtgchrzzuj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbhyjyelf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtpjwwcsba.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtpogiznxn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtmwsvcazz.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohmcemcz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtaypxwjqq.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtdkzugerh.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtyxwpmyyf.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtehxxekoc.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtvheavtfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtuvnghyav.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtymxhljqe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gthqypilei.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtbjsmpwes.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtxqsdmzqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtbdnqzewf.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtdjlgxuti.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtkykfmwhq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqiejlou.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtilrfogai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtlpajytfw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtjcklrxrp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyrfkvlz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtlmvmowjy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobozkixm.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gthlwiiywp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gthqtkajit.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtupwedrlb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtnplrnpbm.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjynytcw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtnuvrwogl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gthmkggekd.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtonefqwbw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtwbopqaql.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtknxvrclf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gthhcevoph.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtcpmwvumy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtxcmanzzw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtyavoqduo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtivmmfjsc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtvrwxobfq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtfzoozuxt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtbolnutmw.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gttudganhh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtegnghgch.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gttxorpkxj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtnoehkqru.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gttwggtjrk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjprndpkq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtavidudfy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtaudxmkwt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtkkyovsrq.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtyephqiwb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtsmflanrh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtiasefppa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtvzdxifvv.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtizfoqbwe.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gturnvtqag.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtjpcxaedu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtdebmmbno.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtmdgczatt.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtiyczskty.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtdimlyltq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtksalmaas.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtwshywmzp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtrnhzkzrn.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gtimfmbamo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gttrupinuu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtozjegqvn.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtatuiylam.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtzsdklkmg.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gteinepdop.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtsepylfkb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtcnxmfuhn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtulgtnksq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtspxcfqns.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtewvugtys.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gthlcsrrej.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gthpxwdwsq.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gthfjlzjfh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtgjkmenyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtfhtrezlg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtktcmdawb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtnowmgnet.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtokcrjbfi.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtnmbcjcfg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppobvruf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtzwystnjn.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxextfuw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtbaolwpyr.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtlfdvmapf.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtkmhvbtgo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtmdiwctnx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtlgaortqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtocusfmey.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtrksxstic.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtoufovvju.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtkwaygnys.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtoiqvatrk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtrzbmjbps.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtedxgsqyw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtgpdouluw.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtykzxtbbw.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtezhjjfbw.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtmynailrx.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtqwgauizk.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtvvidphzd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtxetvdoux.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gttyvnljor.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gthgpgfpcw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtoikkwmjb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzigggcy.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtqhvdymie.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtgglnhroq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtsyxhtwdc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtednkwlhm.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtquqlfmse.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtodzgpjbf.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtgvpkhpny.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtkwuiyfgx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtqtvbpphf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtvaaqimxj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtpdolbyvn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtweeomkxd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtperhremx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gtfhksuaqt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtphkqukaw.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtgadvjyfc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtyjvufmbc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtmrvafbyk.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtkrlqfgpc.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtfkpyzvmr.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrqppaoz.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtbkwagafz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtvtxqewvw.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gttlujirgq.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtvnhxohag.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtlrqpnhyu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtqeqyghds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtpipywasa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtfvakkipk.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtsydxqhjs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtflmbalyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtqzpjdnto.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gttqkhnqno.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtvwhibouy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtumzbtcmi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtocwprhwq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtokraclcl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqzzusok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtngdbsosl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtaounbxwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtllnfiitk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtreyaauka.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtyhmxegml.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtfhsuowqn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtzfwjlfxe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtbcshcnum.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gthzxlmulj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtqkfgkqwl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtpqyckpuq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtddxsfnlu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtxclprvhu.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtxcglkiay.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gttilzwylc.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtulppkouq.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtkwgnhxxn.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtmqlkjbog.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtoaarrepk.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtymhndsvd.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtzxzaukxq.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gttirvpxbq.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtewhkgpbl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gthdwhmtfq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtjhgiunwf.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gteirjakyy.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtjihxueoz.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtwxrcepih.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gthculuaid.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtgjvplhxg.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtdbshpesl.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtnqkcjxhf.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtoqryvqjb.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtyxxosbma.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtwanmsgxq.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzjsbiac.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtsxyokmsv.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtgrilrylw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtducjtghe.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzqwnxtkh.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtzdrzwljz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gttgklftdf.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzppszzo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtyyscjaoo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtuhkxdyoe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtufcoytli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gticpnarts.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtgpifascl.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtkhryxvpd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtczgulqom.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtayjrcuwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtswuygnly.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtcxewjzte.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyuppwts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtvowekdfg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtzadrmpfp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtpfegsuzk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtdhqzdwru.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gttxizvxyb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtuvvicz.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtoaltyemd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtdwolrfuy.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtuclhsaah.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtptkbfcjv.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtbrnlpmwj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtpjqhaxii.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtpwrkdfda.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtskgbqppe.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtsxypbnqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtsoecmzaa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtuhbmntzq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtekyclhog.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gtvgqplzbm.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtvdxgrmdg.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtxtapbalq.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtwhdromlb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtlsqblbnn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtzrqwckqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtspmwvbay.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtbatdjdkc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtfepunpld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtsjicwxiu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtnuxqtesh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtzierwvdn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtekefcxad.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthogxjloy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtwgifzyed.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtfedlfeww.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtovvpwhiv.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtjrnsfblz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtdhzkyznf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gthhcgozje.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtoxdkcvyi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtgomfhucw.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gttumupxwp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtqsfvdmir.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtipzewnue.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtlmbxrsht.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtnmdhfyul.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtoukwzofw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtybrfkmuz.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtehrdbopy.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtitruespa.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gttmsrizsu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcxafslof.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtsuktmian.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtidfpbsrj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtcdcoukfq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtplruigdq.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtypkzrvsw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtwqiguyjz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtjuxhvtic.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtjgvyokvz.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtepvgstpk.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtwcrftncn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtyypllabh.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtmyamptdm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtnnwonoci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtiwecycpu.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtdxglncvw.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtbhxiigpc.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtlqmxspvf.html


<!-- 参考信息 -->