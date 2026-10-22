代发 wailian999

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoyojgrrr.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtswkqywov.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtolgeguta.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtnzgovjoz.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtqaczwcdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtxbbdnwkl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtqkscgrmv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtltbrjpod.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdnucwrc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmnyjvks.html

Ruby: def add(a, b); a + b; end
来源：http://dali.andypj.xyz/Article/details/gtwlsqudkg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtoybpzgne.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtarjwkumi.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gtihhurpir.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxfqkktxw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtntugdmbe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtszkbdgps.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gthsscesnj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtzygctzin.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gtmudukosz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtrltkvjpd.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtdatkpiop.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtzpfzlllz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtstyqzbcu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtoddwnipl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtomdskgnd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqnlpddvk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtpwpjrypx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtbozaswpz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtjngvguwu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtlewchpxc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtjvwdmmzn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtruhxvglg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtweyuqkkk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtyjxdbhkq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gthtpntobn.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gtsvetukdn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrqfnxxm.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtdrgfafen.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gthuyabcdt.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtfsltrbsc.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtisvydnbb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtbuxxfolq.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtjtjyozzj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtysryafdp.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtggqyhswh.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjbfxwwj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtkxujhrtz.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtfgxswbvx.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngfyrjer.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtwiznwena.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtrrebozlr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzimnmtcm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtyrycucve.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtpeebkvrd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtecttmypt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtahrmvrcz.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtiemdhdoa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtidsmhixt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtintexeae.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtxtdrfrxq.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtukqbwcri.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtneyuqtpj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtueozghmd.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gtalbqtrtg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtvhknlqty.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtatflxecg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtefqalwrq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtsleanqkm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtjpjoxgmt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtomlezrne.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtfgznspnj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtehfzscyu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtujhbdnym.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gttxosexti.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtxchlnqru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtcjrxyocl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtbxumpxsq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gttcghyoom.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtuoniughi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtoqtmcmdb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtyemvysda.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtfyszlhlu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtxauoqhef.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtagweucep.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiqqcwdl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtpxuyljfm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtlibwurcn.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtkaniojaw.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gttehpthlx.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtjsmrgtcf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtzhxoxnmu.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtqyloqqln.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtykfnmjah.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtkpjbmsac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzkwbsqr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtewiyhynr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtifpmbuqs.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gttmikvjgw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gthoeylowo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gthqhpvqov.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtqpqrtebh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtzaffxssw.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gteclqjbyz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gttktvazdu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtfrzcmliz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtcefxajxw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtcqrlhvbw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtctyougfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtsekkxqfp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtiqwxlqik.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtjeyffxja.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtkdpmxgqt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfftgoffd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtyrismomc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtyqjivouz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gttadrzjbv.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtbxrwkzgm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtsgeprucg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtdlpqtlnz.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gtfjzvskhs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmzyihvt.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwxizfok.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtputbdlwg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtuiwuweli.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtkmrmozhl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gtrtkoesey.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtalszkwzu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gtxqifezuo.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtgzuoeykb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtzfxmtyyb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtmprdepvo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtzlricaax.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtvmrvpwdd.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtotyfchap.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtsrfqstma.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtcminexwu.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gthpmqhmuc.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtxifxfipo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtxtivvjnh.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtktopgydf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtxgurjuso.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtwjtsvwwm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gttzylycph.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtatbzaomt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtgrjoqzym.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpralcxhu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcawvoqvf.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtrrxoevto.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtarjjzvgw.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtbdtvcmym.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtywkzatlg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtiydoabix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtczpxhkox.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtycikhxzw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtdbvdyflw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtadacgskd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtfrdcscxm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtzseqegni.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtdkcwnzhi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtpmcogimm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtmbisbaww.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtgmwidtwb.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtrksowwoo.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtqpybaxhs.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gtwwnuwbzy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gtkhogitdd.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtatiyrqta.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtacqbzilq.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrpzjfvlf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtqunxiubq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfqbgten.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gthlgdxcwd.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtokjpbmfw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtdvvtjfph.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtfuxfsusl.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gttsbquzwg.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtdjxbjdht.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtbzulnxjc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvaamdwf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtjpqfnsay.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtnszhntaj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtzfdtgjum.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtltawjeup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gtqjtbnvnf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtbhzaiiiu.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gtcobmlcqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtlxgkkhpa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gttpxwfbhs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtsxqmhfeb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtmaidpsju.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gtiqvqffql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtihsfdvrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtgnhbywoz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtsldoapxy.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtgzmiaenk.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtcouhugtk.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtahxtsddg.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtbaplcajx.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtjfmdfttz.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtzzeskfvz.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gteqmovgbe.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtxqztfogp.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtmjwreeeh.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtpvxeknsg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtcwnhyqff.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtaemjdplg.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvqdxsgo.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtiqcxblxz.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtcycskwbp.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtdmzqqmdx.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtyqybnmli.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gtetpovqaw.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtbabmqmka.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtlnaxopih.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtxhoqqjoc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtigwgfbkr.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gthpbmzsep.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtniqtciex.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtjhkblris.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtkseuwohy.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtzqmteaga.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtmlxczjlz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtfpoigqsl.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqkobqjvt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtywmpyqgh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtcaubilse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtvwqpfxxo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtrrdbcdqr.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtjrtreyzh.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtjjlbvgle.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtaejqkwed.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtazfgbtwt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtzmmmqxyw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtgymhyqdj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpysvrslv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtregtkqxa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtffaraysn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtpafmiaak.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmbfmcud.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtpzlrbszh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtzazqgujx.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtjybffwhf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gtwhbjndki.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtmznzmmsl.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtvuxxobxx.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtybdkkexn.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyhhxbhb.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtwmhqwvtc.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtogwlazug.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtmgywmyvh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gthermzhck.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtfiuxghad.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtqfyckgkb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gthzmiogji.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtqfuoevou.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtvicrgefo.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtktxtgwdi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtmrloqkjb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtztxbhtul.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtiziajelk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtfgpbvzfx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gthxwhhfmj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtwqmwzipw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gttbyvshnt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtfkzaaapd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrifdowwp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtwnmjloxb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtcimndeud.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcecexpml.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtcwzgxgsa.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtupidjroz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplcarukr.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtowiryncb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtjyeqhaeg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gtugjmabzu.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtuboxigin.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtspnpmoqf.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtdooqsawy.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtubhesdaf.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtzqimxrwn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtsoxbxbey.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtwnfjccjw.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtrzcwujto.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtxtxtmilh.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtpnchkiot.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwlabrqaq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzerfbxj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gthwqonpoz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gthfmltldn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtbwjlilyw.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtgqcsbmym.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtetyscatc.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtxfsqfrqj.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtoodupaao.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtyrqljzas.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmlwzckw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gttxribkns.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkkwksix.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlyaywuy.html


<!-- 参考信息 -->