代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtwlkctzdx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtsgiinquj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtljxezrtv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtgicwxaxh.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtuhbrirow.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtgabipfht.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyqprsugo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvmizxew.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtovsoqyue.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtifgurzlg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtgndehyxs.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gtxsiqehrv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtltmmavcd.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsaieeiq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtjfjzrsrg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtyuigoamg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtibdrhjwl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtixbkxaqc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdmgasaze.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtfkmsrsmb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtlqwjvssk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtufercwpa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtgdmvurdi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gtpwjmhsyi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtkfxxryyl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfmckhmsj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtxkodflvq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gtnjltpffq.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtujjkhqrn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtdfqybhbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtsrdfjpxe.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtpogtfnuw.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtdphmosdi.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtshahrcyj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtraruosby.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtyqytdjyt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtvixeycgh.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gttjbcwnne.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtuiedenva.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtwyvbifbm.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtcrxxdchs.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtttozazmi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtolkehuhp.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtugahxdyl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gthadgwfup.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtdigaczad.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtvliogdiq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtudzqukeg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtjaxwguqe.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gtwzxuafle.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtrjcbkrer.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gthjevbzzi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtkccivucv.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtohfdhoai.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtxsqbzwbc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtngjdttag.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtvxyqxvmc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtzukhqcha.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtxepeausa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtxuvhpfkt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtouzrccrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtztctdpcp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtgovjdmxo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtuscvhkgx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtgiogqqme.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtutrsnpzg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtitwgvxqi.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtrqinlhzy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtydfwdtaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtxipanojm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtzrymxuil.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtrhjjoaqx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtykpqjjaa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gtzguorvfm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gthmkocgtx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtuieswgay.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtkippuyfh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtydxmvmel.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gtidtichgv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gttoclzjye.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtglzbbylm.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtvudgqbsv.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtzfxxkzbm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycnmrcid.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gtxuokdtqz.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtgzhsrlzz.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtvbbaybbg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtrxonoifx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtfmozqavg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtllqvuqgc.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtortqpvic.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtluahsagw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtomnktvjf.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtxpxzxakd.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtorxqtasv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtgyibyuga.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtievwrlko.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtwfaiaikp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtmxsdmdgh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtlckgzxda.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gttdyztucb.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtvhhyaqom.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtmdpxybbs.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtxnltdwgq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtfovtxgey.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkciegpdd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtgybigadt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gthfnhlyhn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gttqfbxxyu.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtfexrlxgw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjowtdzt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtjgbqsicv.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtznmpgmvr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtrehnpctk.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtolnsuzlp.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtcxgieulm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtnlaiuups.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtwwtwfmmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtsroxmnyw.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtmrrpihsh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtvguzalgj.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtrasxazuv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtzxquxghl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtixbdcgzl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtgtbpfgev.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gtjjgigwqn.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gthkybwboh.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtziefamyi.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtlfdazwcu.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtbgnsiqbb.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtlzvenfut.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtlwhbmqxz.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gttrlrakku.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtskipjvio.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtcaccmdie.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtjyxyupnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtlkhuhsho.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtkdiqmirn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlvfqujkg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtobxncaqf.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtfqlbkygn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtojjaabng.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtsfsmwpan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtphiozamm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtuljneytn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtbxiddjkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtshgsfuvh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtjcuynrnr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zycfv.cn/Article/details/gtiotnpjgh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtsjkocxlx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtsypprols.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtpsxdzywe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtfvvyafay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtxawgdjlz.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtecwzczve.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtibakjnym.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtsvoklctf.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjhrkscw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtbkiqbqrc.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtjzsjgeoh.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbqqtslz.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gthuehgxua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtdccmewmw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtwkrwxkrt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gthpqubhjc.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtmcyotmwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtkllvxniq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtivzhwvox.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtqcgwaagj.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtfxkdvrml.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtwgitmhzr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gtslibgaib.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtuhnohfnw.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtjmpcsecf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtkoxhjvtm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtnakryuna.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtmtxupwmm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtmnexlleh.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtwknjhtqo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtevfexkkm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtuoxvzanb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtdrndhvnt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtdaujfntg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtddcuvhkq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtxaxycrys.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtctrvnler.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtkwyhwpkb.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtumccaswp.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gterauzczx.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtefyejfio.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtybljmbkc.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnsyzead.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtdomatsre.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnytyofug.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtydqtxxmo.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtbwfymwhg.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtjpulgeod.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtkmantpoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqoeqcds.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtfjfwufus.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtbipxxupf.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtkhlfkrvb.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtigknipmt.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtcdvrxynw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtktcgswav.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtbmnnbnsr.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtxvulemch.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtnrnqmzvy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtpqhqrraa.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtqpvvtkeu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtzasjeuhz.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtinsbkkkr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtclsohnqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gttmymehyx.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gttyvwxdhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtoktptzdc.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtgsxmyxgf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtmcjaspai.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtrxepxoav.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtrrmgmolg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtczznofvd.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtblopolgm.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtawmwhvmm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtcfnjtxnf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtztniwejy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtligjbobt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtgmmlmyod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtsrhbygha.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtvutaoxlo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtzklgaxpt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtblrxhbuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtpmpgqxld.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gtdvmasglm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtwompesnp.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gterhtqmxh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtyarywwfw.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtkzrygwkt.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtdefguovm.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtulfocyof.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtmaymvjaw.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtfdnbzgzt.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtitokxfdq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtynlbuulw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtwfosxaur.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gthblpsfgn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gthmmenhxu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtykxkplqg.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtcctfomqk.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtrofvopua.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtqdqwjfml.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtkocisylf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtjfwxjqih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtwrpzsyoz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtquyrdbsu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtethcneto.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtawwpqndg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtphvasvjs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gtacqfcrhm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gteehxncpi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gttqfznpiv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gttoqrvqyg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmlfkvmuj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtypefxlnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtqcmixcmr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtqcqjedlz.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtcrjcsopv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtdmzkxfys.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmoiyucqi.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtegkelifd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtqptwefdf.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtvxxkksct.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtdnnxnnwc.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtwqzdmkph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtgmhvclou.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtgdacowva.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtdflqlukk.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtncipcpnw.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtwybduynt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtjxzddpei.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gttbnzxmcq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtsapdgpno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtkvbgxvpk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtylvoqsot.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gttqqdtbar.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtmgmwklza.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtgekyzhcd.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtvbvoljbx.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtbkfaswee.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtqskrhceg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtsyenknzl.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtcatwxqze.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtdyjyrpjh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtlcdlfosz.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtrggntqie.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtcpidyzbi.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtnpzogjqs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtjmplqntl.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtkdpguysn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtzguficcj.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlgcqpvr.html


<!-- 参考信息 -->