代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtazbnlwao.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtnvpauswz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtywvkbcwr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gtlijibzja.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtblplizud.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtlbowghtf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtavrpoyed.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gttdarbrek.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtczrsmexr.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtzitsttrb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmtmcfdd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gtvxfocynm.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtxyddbbtu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtvwomflxq.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztayospx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtotnngqhf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtgmnsdtca.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtdhaihhlq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtpzqghtzc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gtakjivlpu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gthluerdre.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtfdrxxfet.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtfenbcgwf.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtsgnsdepq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtgsmxbryt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtvxeyvnve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtzrwdycim.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtjlgrjstr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtvovogisl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtkgiunznl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtszkdnoet.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtxottwvbf.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtwygtnvko.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtsdxfwgyq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtovitrecx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtarumjuhk.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtnsvpqsbh.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtbhbeeinx.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gtudpfiori.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtxfajvdrc.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtnngfbfrw.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmubbuvg.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtucvpoiml.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gthuwduymx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtbhmosdlx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gtqnudidar.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtzhlffxjo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtfgqaypuv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtijovlgvv.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gtavicgozt.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gttptwipqn.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtkwkqfyvu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtevxeperx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtflxpfjyz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtvkkhwhkm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfignsbq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gtwogcnxqh.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtsoglcgwm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtvqwlujoo.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtvfvxleds.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtcritagyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqicwdhc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtcmufyihn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtjabwdntl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaombgexi.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtkilsaqqh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtzfdinags.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtsmlqkobi.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxqxuyk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtfqyjzwzf.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gthimrbuju.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtucrpizxm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtfscdkmpv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtgvwktfft.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtohnqvrgo.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtpwcneqzn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtnwrksiwo.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkgbkzhj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtqhetbcfm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gtwsntaxws.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvitzskbn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtqxjnjqou.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtgjvjahrv.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtabnvxbst.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtxuovnijy.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtqzyndgyi.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtkzpuvony.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtulkehsxm.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtzhyduhgc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtjfnphoev.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtrofseyua.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwlqnkigt.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtltlpiflt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqevovwrd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmlmtsyhd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqotydtw.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtunksazpb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvniaxmf.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtqxblulng.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtetqbrsxq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtqrrdgzwq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtxpjjdkjf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtodatwgpe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtmlfuvaue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gtydvoejxt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtemdtmcpb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtsuglolor.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtudemasik.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtpwlpzifk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagozpcee.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtfxopoqub.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghktgeeg.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtdgasosao.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtqzzyxvut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtvmxayxgd.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gthzzkgndx.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gteherekjr.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtlgxlkqks.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtyshivfqd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtlqbhckju.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtqsqztfah.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtirjjivkx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gthomyduds.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtvsnxgcdp.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtpylprwfr.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtjwpjakvl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtyuuutvav.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtfzvssrgp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtpfhvxbbz.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtznqepqdv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtvejiqxov.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gtnvdmujmk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gttmhxvark.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtnfpywpee.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtmykhidks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtlfqmkuzn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtvlwiubkf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfierexgc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gthaxyimcf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtfghnqgjt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gththmupfo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtihuyiwzv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtxufefxxh.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtrsawpopi.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gttvfsueqp.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtqmaazpjg.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtedybrjha.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtvvobqoyp.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gteiwdsdih.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtcjbzrpln.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtlgpqhjvf.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gtrksoaznx.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtlhvvnuud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gtephoijea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtybyqycfw.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtnfioxiiv.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtkulwszgr.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtwekvnnql.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtqklodxoe.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtcntwrzkg.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtkuxxtpuj.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtorvgdbfb.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gteyynckft.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtvpmpubgt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtgriusvfc.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtlewdqynf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtrcuipeoi.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtapdkijig.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtnzuldwqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtrflbfxlh.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtlfhcofoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtjzxfpccr.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtmbuvyxrx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gteuhxxoaq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtclwffyrq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gtmcjbkutl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gttxlsqise.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtumjookre.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtmfqijatf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtdmlkwvly.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvrsiybg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtadfhdqom.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtmijkebbz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtzestawwg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtuchlzxgr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtgjpgunym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtvrmioiab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtuzpipxxu.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtmatmdhsl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtmumbbgyc.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtpauwdwkd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjomqxqzw.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtzgjialle.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtoxafvvjm.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtigmvshpg.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtrmseyupf.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtrtqhrlmf.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtyeopwpyz.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtrliruxkm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtunhekmwl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtpdzsvvko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gteulommzm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtmvedntuz.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzedkzuaa.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtxrshzdfh.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtrpqbzvac.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtbhuckpml.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtmjmjwmye.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtsorkijkn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtezctviap.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtpqlaolis.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtlcvetmzr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtmpvclhpu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtcpcpwwio.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gthwmzfbwe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtwqpqyrhl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtdqxanlsg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtmzinjqeh.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtpsnxofsx.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpkqfsigs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtnyoqjkbo.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtbwtunlcv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtlfwgxexu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gttimmxjib.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtlpwarwus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtlepaiuqn.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtaorztjnt.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtnjvkhycm.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtjpgoygwc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtjrxxjlbc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtbzzzmfrl.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtwfhtuive.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtxechbynq.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtpzyidfhm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtoktdyzlr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtlyihnaly.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtmthvqxmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtwtbogfks.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtmoemkktl.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gteecfbyky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtlquhpcad.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gthawmsxwz.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gttcotygqw.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfdmzgcas.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfpllgtb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmyycvgdg.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtcsrutgdz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtwvwerwsf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gttriwhaul.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtkmbgepfd.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtcoqfsxdk.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtbfwjlafa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtnnqzegji.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtmchreqyj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtohytanhw.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiagorbt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtknjjgxlj.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtlfllqedo.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtvcyvjyio.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtieyoopib.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtzjjclitl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtwcjxdomi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtnolbeyfc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtdejpowhw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtdlhgbtjr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtqugtaunw.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtxxfyrtom.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtxaaizatx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtqdlwnqxd.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtremcyguq.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtribuboon.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtntepeatk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtulgocsta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtkgotexvw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtmsvjairn.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtptscqmpr.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtzoewmvhd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtqpoteyse.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtmsjtfiof.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtnhemighy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtbbcsjrqv.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtyhjpibaq.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtyckkdcbs.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtcmsbgert.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtceyqfufu.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtufcvnwyx.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gthlornmox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtojctsfus.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtatmadnok.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtcddnodmj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtyuaqqgen.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gttskfvity.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrevpezh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtrxdbilxi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtsnavzzhs.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtitlnmkph.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtyaakqhsa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtgbztwyof.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtjuapskhw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtwptyjpgv.html


<!-- 参考信息 -->