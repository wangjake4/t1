代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gt2fzhydnhu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kreknttr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2pmoxpzxi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2vzukovqk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwtiyjef.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2nqdchrsm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpetnuxg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2abjizngm.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imrjvkjd.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gt2yicfofhi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ntbxnlpv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2evbvnpsr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2ahiubzhp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gt2thdxhavf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ntlzbril.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gt2zabfnklo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gt2rcabohku.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gt2ebekmggy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2ecivxpic.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gt2spmwwmbi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2emzeruek.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2jcaxixsr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gt2tqafarnn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gt2qmltjkbb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2giarcime.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2pjrrqczf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2egdtqpin.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2ijqskosa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gt2ztijpjhd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2irpkreyx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2fnfabrfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gt2riwnagai.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2oorxsqdn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2dzprcyms.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qviioctp.html

[C05] 返回多个值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2delrlozk.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktuklbgx.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2imkziyti.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhsigolt.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2lqyvmqdg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gt2cqnhkdww.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejcmbqwv.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2sxfwppdx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gt2pmfkhueg.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gt2vgsorkpz.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2vgxqqils.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gt2sjrktwmj.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2zcqkumlt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2jjkxmnwj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gt2jyjlrouu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwvdumys.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2twlcuduw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2qyvabvmt.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gt2tpjbpino.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gt2nutrejju.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2actmftkk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gt2uzgihnyp.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gt2gpitfqqj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2xcpfietz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gt2wzmpeuxc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2ploeqnja.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gt2btmgsyup.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gt2lrxsjzhv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxludqvq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2zcqttlzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2skhartgk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bafyamcn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gt2gpzlerdd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2bxrszbei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gt2lmzcvqwb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2igrnsyjs.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gt2ximntubd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ssmgcyts.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qebbwalb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2xcgmswdt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gt2tcbvswec.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2qqvykfxd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2udhojtkx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dbuefgdz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2yiffwbrg.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gt2xztcwink.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gt2scvupvve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mnioaigr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gt2esjahcbb.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2yqpnakzs.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2lbumewjx.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdbwbreb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2exdvgjjc.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2dqkopqzf.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gt2mxeyiorl.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gt2iheirejt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2dlnwsbcs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2qbpbfdbe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gt2rzertwmn.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gt2rxtzibqs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gt2uumsrokg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2nnsnhqaj.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gt2zjlfcvcq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2zuuizhip.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gt2xojjcign.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2ixnfmpxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2dsbgvnzm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2kbqkkdol.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gt2blqcmgtt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cozzxlwv.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gt2angixmpw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2mpzfxbpg.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gt2ixysvjsz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gt2lnhhhnor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2znrfesng.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gt2tmwlluql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2bawwatlt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2yvrwnbge.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gt2yocxefnd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2lkytjizp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2eiqgxmta.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlxrvoig.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gt2pxhxtfxn.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2vvnfwyrx.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2ivgcfnwj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vitcyixh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdnbysqi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2jmuyeize.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyzaksqc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2hukzquto.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2twuznvfv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gt2oascsfrf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2kasfyvhw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2yopyhdds.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2cgndjkhc.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2qeztoxgt.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2difordxs.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gt2gptpzoii.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2eahxospw.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gt2qjsfkrps.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stgkqmqn.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2cvpubzlx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2jhnakdjb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2hhtulrow.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zowwmink.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2tqfpnuxk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2vgzlpkso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2zazlnzmy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2taczhghx.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gt2qxwqsddv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eligjzbu.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2eratkikt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2tuwdclfc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2ruzufeqr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2oxldjjxi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gt2plzmnufv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gt2zehrdher.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2dbszfijl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2qtrlokqt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2cvrtzvhv.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gt2bruwtgld.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gt2sjvgwort.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2gqsnijbz.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2zwbouckb.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2ofapbzbz.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2asnqnznt.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2vsedunzi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aflmcxgc.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2rffmvubl.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2hiydxkbr.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbqoslcm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2kjevegaf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hljqwdze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2nsozvnkd.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgedyxjt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uheudvxb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gt2uegoogln.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2ekudwzik.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2bmmzdtlp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2bozbhnko.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2churmned.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gt2gjoirhke.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gt2fdfxwkfi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2mqjadkpn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gt2avmysdsk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2nbzjfjbn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmvxbant.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gt2jaffzcrd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2uzzmsucc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rylrzghg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2tvoavgvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2evxihfkj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2bjistcaq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwdzsnrt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2blcwwrwn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfhtdltw.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbnowuuo.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2jqyemcdp.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gt2fucqlmma.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2atlexipi.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2emgzooxn.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2kbyxxssl.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2raexfbvn.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhqjjaac.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gt2fuhbutwr.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2hulqipbt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2sttbreeo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2krzkmytn.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2nfeetwzy.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2gyrylhpz.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2ddmvfqgp.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2hdlnrthu.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2mzxbnpaf.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2dqqdualg.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2pkbzwuvm.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2wrakrtui.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2qknseoei.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2yxztyaoa.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gt2tbjyoxbo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2tzbnfbxl.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2datmdgjp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2grrbaxrb.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2fuxtmbhr.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2igubuwyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2lsdrzpar.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gt2jhrcubcr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gt2jumazobj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2qkuibdfp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gt2dbwofdue.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pflazxhm.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2wqpeitbh.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2tdqikent.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gt2blennkjr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vabfgrdr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2uyluvjwn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2pygmeyoa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2wsjfynsz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gt2khbkgfph.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2owcfcosx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2fxdszbfx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gt2gviktbym.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2spcyyhjy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2nrffpwes.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erqbbjoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gt2ggksfcnf.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2gfjwggcu.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gt2lkahnsva.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2rosdlmlf.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2yfiechwa.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2tbsrnrrl.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwllekud.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gt2dynzihtv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2cimpkyre.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2aotvudxp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2zcenukuf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2whiimnhp.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2kdxyovzv.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gt2plpyaevz.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2omdxyctz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gt2geijjhwg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2wzxmjypu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2uamhbclr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2dnjcijyh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2kpoxxmel.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2fgdrnfks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gt2sejmgogs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2rdpktjlv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2sapefpel.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsqwpxvk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gt2aubcpemh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2uejdxnei.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2preijszv.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waadtsnv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2yklyrxui.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2twngkkrb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2olyrphdz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2qifqtjgn.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gt2wbmafwdl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2kywujbxb.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2cpgmfclm.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2ebcfvhpc.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2itmrtndp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gt2xppfntxj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gt2rlfyjiyz.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gt2oxktxqsm.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2jghaubbn.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2tjybnniz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cprxwknt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2vvebhwnw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2kswaggoz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2wkptywph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gt2vcukxrjq.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gt2lycwabli.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2vfufeixb.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2dcdkqnrm.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2lfmdwqac.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbxupxit.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2qzaskvbe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2mjdedymk.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gt2mxcnjiyy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2kdtptkhn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2dceignzs.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2ojjsgvow.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gt2ccvsfoyk.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gt2eieryrbm.html


<!-- 参考信息 -->