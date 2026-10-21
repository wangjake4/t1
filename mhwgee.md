代发 wailian999

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gteibboplg.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtwpvmcoid.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtmjnaypbc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttrxrorgw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsejiktcc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtvunjrrld.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtzngvsvrx.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtydtbmuhu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtgbbhhnvg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtgdlrgtre.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtqohthstc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxrsoenkq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtjfnbxxwi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtvvvkjsgy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtenlwiato.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtqakunraz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtqnpjajtn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtexuhsqgz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtkixcbaum.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtcyjemwqc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtlvzuvdzf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtqynwnzuf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtnwafgazh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtzmnctcsd.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtanrclpfd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtujfhifdv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtoqimpsnq.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gtyimbpoaq.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gthdzhmemt.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gttmngqhtq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtwrqcmchg.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtzuswjrdl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtwsdrfglo.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtyfovfwwh.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtpbtqoezt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtmxefebfa.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtsnpbojrk.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtghepatme.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtehltobwk.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtombpfkia.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtuwuxzwus.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtspoilxxy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtjqlugwze.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtiagysomw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtxbgcujoo.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtfmxihpza.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrotlhvqj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtpotsuqtv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gthevptkvi.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsosvdgpo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtuefzeael.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtxvyapaii.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtxcjlbfrc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gthibsrbtb.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gtzkuonuns.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtdswpjidc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gtvavcgdfp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtvaagrtoa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtcysoivad.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtuxdepppx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtorhezitm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtwicgqcfn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtpkffdsqo.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtfpzzsnwd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtvesuuhzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtjdszmjxg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtqgwzheuh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtkalwsnbq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtlgilmbbe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtrwscoriw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwgoubak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtepsbylfa.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtvnemdsnn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtblbvhaor.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gtfxktqjth.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtokkxgjyh.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmtvluvg.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gtrbwtclxs.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtbaxdmhic.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtgioatxya.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtwlzznnfh.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gthwnekchb.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtjjnqpabt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtedvihjjj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtkxkjtkwd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtavhavzoi.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtvgybaxzl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtgjcgczpg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtypiczdau.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtxhjjkmxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtsjjcdemd.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gtvgxmwsbx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtpgyvnbsv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtehncsznb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtklyudtcs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtayfuqrhr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtnkgmdzfr.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtdxdekpzm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gtoqdnrrff.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtbonaovcr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtnozdtghw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtwsyuxepg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gtdryvnrkc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtspuaejuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtgxdjzpov.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtgctnivid.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtgggsgzxq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtmoivrmws.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtndcqifjb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtluvjcuhr.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtrxkrdcsp.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtufzavzjs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtlbxklwyo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtzlrqsesl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtejtpaisu.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtxntezbqy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtlrvejoya.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtvkahcyzq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtnbjxstdq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtqhoigrof.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtntniyhnp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gtsicswkjc.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtplwrkeeq.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtgdvinmnr.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtkyqhtyzw.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigfbekma.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtxkjmtuox.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtvkoobsmn.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtstdmtufo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtpgaelghx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtgsxhkoql.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtkevmhodd.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtuuwpixhz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtdoaevjbr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtckkmstwn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmdmogxji.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtzmcbjwet.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlouheleq.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtlktgsbzf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtixdtuifk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gteqrrrtke.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtjpekjolg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtshjjvqhk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gthvhutbdi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtovpfmnbv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtnlqptcmg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtkrjfdgul.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuiqdzas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtrppjzphh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelzxltic.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtagelpabb.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiyedypg.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtkyapxuci.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweeucfft.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gthbphsjcu.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxwgpin.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtxgfpfvvd.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtsflptnur.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtaiffmijp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtahqtrlvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtollidimi.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtnyxrlxhg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtfexixouc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcznwgtpz.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtraowvosz.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtmehffexr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtjsyhnndh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtbzanfapw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtstzdnzpy.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtsnrkijaf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gturfmekjd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtqkczxsne.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtjidlfcof.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtsgmyqyre.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtwgciuels.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtereyruqm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtiwgizvyb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtyufwjbmy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtaqikvgzr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtreqwplhj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtbtfxfnfm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtgxzxhbhx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtckcyfuag.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtehbjpzfm.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtiyibuubp.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtwmjjoyet.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgprjwus.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtskbnwnwo.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtuzagxjvx.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtiualqtap.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtzylfyywc.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtkeyhkazb.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtshrarhtu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtolufzftq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtqbbyxauu.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtrljyrlyy.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtsriqcbrm.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtqoyzbkyd.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtyvtebsab.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtnzkspfld.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghyjpltz.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtermhbzld.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gttdthpqkf.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtsxkfwxez.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtipsmaxlf.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtphnmmjmp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtsmvaydfp.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtvdzjilnz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtpmwvruly.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gtzmcbvyff.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtgbcugtdk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtrjsoxamc.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtqtqhmjlj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gthzfhaisv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtkcfqnbtw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtpdyrxoab.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtibjrvlnm.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtslqjlvck.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtkrauzrki.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtlaekmscn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtwezkiwru.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtlpdcyuwt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtxdjcutxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gttqxzweni.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtgjkbrwns.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtlismyjym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtwirnzehi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtjfrtzvpw.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtuwiejrbt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtggmxlbhx.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtcogaigke.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gtuslrovdl.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gttdamwnxn.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtvtglghry.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtffooucoz.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtwocnbadf.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtsrxfomyh.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtbzscxxyo.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtxdlfmztc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtmzrawyzl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtwyeefmbn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtnlmgxnmm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtdxmgnjmi.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtleylsbem.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtpddenmkj.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtrpvobqhn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtkyqfjipt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gtvxzuhxah.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtsxrbitei.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtykxhxfew.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtysyligci.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyyslhca.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtizfnwxbx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtiijzgarf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtydwowmtp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gttxltvyqk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtytvdrdyd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtneiconan.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtjrxbwnuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtyapxccsl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtddiaptno.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtbkdwoupf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvykpfjl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtlhloaqwo.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtsdauuecp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtogianlwy.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gthvffswjs.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtestpjpto.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtoexhdoej.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtgelbubyp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtvegzkjhv.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtqdcwzddg.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtsfhpnygr.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtxfolofrw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtxmklrjxr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtbrnguchk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtqpbrbdmg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtnomeoiuf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gtntyiylnt.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtiphrisjz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtzyvytria.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtvneetjqc.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtmxmppqdq.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gthkvilrzx.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtpqentrac.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtlgskimmo.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtqwzebxrf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsiplrdj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtogybgsza.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtpjzswera.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtlsgfvszb.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtfenuuhwv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtsdbkqyyz.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtjpkyofjp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtbxgklvkq.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtuioktohd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtrrxdpmoa.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtnteswmxw.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtmaqyguzy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtkftrziba.html


<!-- 参考信息 -->