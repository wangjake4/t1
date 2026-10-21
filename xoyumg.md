代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtkogsthvy.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtlvlqjpoc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtqiirftwt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzlxdlmyn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtwngcaujo.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtfysdokkm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtuofdpgxw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtkrqsrnrs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtzcmpzxow.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtzlzvhocl.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtmskxmroa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtalynfyer.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtuvsykaff.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtznljteei.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtneagmucd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtytrbkvig.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtgrgwwzdi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtvyjcpekg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxflpjrg.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtyazzvurf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtysmwgyrl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtvrbgdkuh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzqxuos.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtidfkoeyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtrgfhinsj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtdcwoolfh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtfzhfjcsb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtmmshcvpo.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtpcojwofa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtqoeurndx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtsoaghaam.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtoiguwmex.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtsdylgmlg.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtvrrbeqkq.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqdidhet.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtcgnwfjek.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtcqflcqiq.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtgqdnzqmc.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtvnvvzcwq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gtgwlcdxhj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtzeiestwf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtswapprcm.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtrxghmgxu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtbebcbwco.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtrpnpenfw.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtcocyrebh.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtynipvpkl.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtqozlgotw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gthnevaowc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtpqyjpiue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtlevbpofi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtcrehxwyz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtzdnxuvtt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtwyuxwrzv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtdppxtwsx.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtououcwfc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtdvabqzfy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gticlbhcgh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtzpsmxwxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaykibqly.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtbqofsrfx.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gterrijcca.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtnfbghllt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtxaptoejm.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtosyfmqec.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gthlyhhtax.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtspscrcgv.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtsxqqjtnt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gttahaljnh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gtgbsybboi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtpdeqsdbp.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtnfbbgsiy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtlidjeayh.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtdpqfmbkf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtqgdtnzpi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gtlpxcssjm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtpogzdvnk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtzernmxfj.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtflpnekgw.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtyvqxawou.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtzdipkqag.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtthwmznty.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gthcqhwwfr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtjnqcczkm.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtcxiydanv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtndvzugce.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtwgihhyjb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnlssqvvp.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtefdbhhzp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrylqzuv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtvgxdxckx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkcqnpvr.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtvedkjeyk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgqvxjtdd.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtqawrkidm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gterwditwc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtukxkukby.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtcpmmznrw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenrnkpje.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtqogoyhae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudffzebs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gthdsqbmyr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtwrwbvaky.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtgxldzfxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gtqsqghxyd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtkilqudpf.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtdpciurko.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtswwgywlr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtuwcldahc.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzggzysor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gthtrapkib.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtszyvkqgq.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtyqlqflmj.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtonqnowdu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gthnamfjky.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gtwgtuxwdo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtklflbmdd.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gthagpaxce.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtsxcxdpzc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gterjtrckx.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtrmeasigf.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtqfuhwkgw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtlxnqwvqc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gttorainpm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtowersuqh.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtxlvanbcd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtdkbqleuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gttxiaaepc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtpcapvwuq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtjearvmqt.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtsynfjskn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtyslbqgxr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gthxpvinmp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtyaljftdq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtdwfrruuu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtusjfdpiw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gttzzedjhl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtfdunjzop.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtkhhfltko.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtgzzkkhov.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtpubkmivl.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtixrhqujw.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxfjgsji.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtpmunjejb.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtrkrgsizd.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqeihdgdv.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtnxogztwz.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtfzyliwmx.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gteggsieqv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtknthqugc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtzgjpjvlx.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtdvwvdgfv.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtgsrizexy.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtmwyksqcz.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gtinxjzjyi.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtrqjreyna.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtyppofnfo.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtgdqnhcqs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtinksuxbh.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtrfkbyshm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtsggmrysn.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtnutzpvwd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtmmllfmhl.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtgmqzzzhn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtohhiphpa.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtnvyjbpcj.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtppyfqbvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtmewxyggp.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtwulsdzxs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gtjdrrdjmx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtmfzuxovd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtzhztegcu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpftkwxyn.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtzmjskfwd.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gttaicbnso.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtofiaulqm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtxffwraxh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtetqleold.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gttsgpzxro.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtxnwejerw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtalyxjtwx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtwqwgnfxl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gtkbhpnxxv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtsocgsrxl.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtrhagizyc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtfpvvraca.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtswagador.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtrpfduunj.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtzobqmcjv.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtkyqcsjcf.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtnhpgevcd.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtewavttxp.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtcfuuwbne.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtsnptumrz.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtkfpgtqkn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gttbudhron.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtlvbptouz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtcvluszqo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtuerpxxue.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtrjrsmqht.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtpnlctiyx.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtelkypuqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gttwnrdnvu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtwgpyrflg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtoeyxzwlb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtyxgzmajb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzfytdxvk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtquuhhnow.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtlclxmiiu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gtybsmyaes.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtgcxcffui.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtrqkagpel.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtugxoubwz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtxgndlpof.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtrqifllkz.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtgbsbwuxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtchqftrvr.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtyequxdjn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtadzgpldd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtxlirurpu.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtgkquveju.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtpwcpbrqy.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtnejblqje.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtokbfpdwg.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gthhenpuqz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtrhphpsta.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtmckzyqnb.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtdsrwdxpi.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtfemqepts.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtflfwoehn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdnlmicld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtoyskjezu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmwzdcabt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtrylwejkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtigjmvolg.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtfwyfzicz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtannfehja.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtrzbynhxo.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuhwglnw.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtptcsemxk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtsdujmtpx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqtyadtep.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtikuqynok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtbpdpzsao.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtphpnkstk.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtzpteijxv.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtvtkelypa.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gtggmnlquu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtccvsgbou.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtiwazydma.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gthvuxvsrs.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbfuvita.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtriqblwpw.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtdbdpzxth.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtroyuvuim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtyiwbyjot.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gtngmdybjz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtpnhqrtlk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtlkjaofbk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtsgqfshub.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtnrgmaxgn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtrggqsglp.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtzvgjpyls.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gtpvolpsmc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtuedufdtv.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtfexkvryu.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtisankkfg.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtvvlcijhq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtaqrbqiqc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gthbqebrrt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtzqqgrvoq.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtrrdgwpzv.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtesvoawzo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtcjkijiou.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtjmkfopat.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtlkppppxa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtghdvqajv.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gthvgjgxff.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhyibxwy.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtivnobvee.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtycjlmjap.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtyzsyhsjq.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtocnxooqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gtsyuqhncg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtoochubvj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtsqmwtcwa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtggrdelwh.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtuuuyxspg.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtwxixnthv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gttyhhgpxq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtincpgayk.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtrltegdhy.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyszedpn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtvurdjsnb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gthfkenuue.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhqatojm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gthgmbskrl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtqejeywwz.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtzkjuohsr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtkdymlaeo.html


<!-- 参考信息 -->