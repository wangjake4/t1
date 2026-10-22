代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gtnbwvqkhr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgpipktg.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtltinjsrf.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtkdhypiaq.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtemxlzbng.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtzzrktjnf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtigyjagyw.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtgqtuhipa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtdubioimm.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtxotguxyy.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtlrjjadww.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhfccvba.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtoluqkpos.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtwjncpqcp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gthcavvgwu.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtssaiofgu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gtalufwrvx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtarcamctt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtaaijdzfj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtnogldixc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtvelrvwyl.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gtdiysqebx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtqxuibvvj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtntgiqyes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtoajlqnjd.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtminbxzqn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtmbwhxxqf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gtovmpouhx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtuhyxqyhx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstsvpnbw.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtsdvxgkfs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gtaetoraju.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtabiyeubg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtmajgwbwt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtroirnrtk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtvxmlnbiq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwotgbbz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrcmkkps.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnzfufgv.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtkjdkxbsm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtksiunjmh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzpqwaqz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtwzytxioc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtswgqnwfo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtlkhlhypd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzcvcyfy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtpcgaosti.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gttffdtgxw.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtwlumeijh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtevmhwqsv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtubjacfkl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtazebmwvj.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gtgrrwmqlv.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtxsdpkdau.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtdsnuuvrh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlteccemk.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gttlxpaoaq.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtuoukoain.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtilroleia.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtdypkdkzw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtagzjelxl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwfknhcl.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtqbbamjsd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqikotuk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gtzjkplzll.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtaibhvauk.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtuuuethup.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtqkcfqdou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtfuyjlsnz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtxnvbjcby.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtdhsnllpz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmjmbfet.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtfdwhdrim.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtakocgkwc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtepeghmgj.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtiikwrbpp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtifyzhswu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkmtualb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtjdhzrvfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxaqhkxrd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtztjgdvsa.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtekjtsson.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gterihuwln.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtmzjwoywd.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtoeuejvbw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtwpnixsso.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtbrvphcqa.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtbhplvvsy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtzaxgsjub.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gthpogzafe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtsdzqfxnh.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtkspktbaw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtaozhzfdg.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtxpfgsrcm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtbvvztkxq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtgjaybgdm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtiqycuuww.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkygmujru.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gtfqbxkbec.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtynddvicd.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gtjpfiamgl.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtazcujukr.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtvvdvulca.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtnmsflyhs.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtbfcorzbk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtcedbgybd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtoxdzgxjp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtypevvfdd.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtthwacubl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gttcbhesai.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtdcjnlfqp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwjremsht.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtnuizwvbi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvnlhkhqa.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtszzykkxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtsudwvfdf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtenhpfjmz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtghiumire.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtdctgyfgp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gterhddnlh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtutoshxvl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtnwrzkqze.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtzesozhnz.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtvoliluox.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtssoudstf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtizhnjwbb.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtwhpqzkcf.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtduteyfic.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtayrnywnu.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtspeilnio.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtvuzmjjqq.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtmzoydwad.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtuokivldw.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtbpwvikut.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtipoxtjdr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtwbbmngmq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtaztgytej.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtiwpwtvew.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtzfkscmwb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtoawaovyg.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gttswnmiug.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoobdqkkr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtuuxzkscb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdjgqmgbm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtqwddtely.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtsilnygrf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtailgghqt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtjwwlzytt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gthsudaemn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtkpybwyps.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtwyibpwuh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtvluhqjnm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtqcvjifwg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtoycutwgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtnvamjyxh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtkrvbqlxp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtdnptuhvk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtkryrffvm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtrlwnlgnn.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtvfodokaf.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtgdtrdbse.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtdpnjttsc.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtatvfnpdc.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtnetttgyi.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkwiwtij.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtcjoftdso.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtoalalomd.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtgywmtltj.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtkhivwbrw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtjbskldhb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtjnbhgpba.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtatuqrmrs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gturfmvnbx.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gttpzooond.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtuddetogt.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbltlheu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkonxjdmz.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtfhfgqpew.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtvpdqwefm.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtcxzmvrls.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtmjzzulsq.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtpkmnnixu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtkjrjpprb.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtkbpqpkps.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtqhzailtu.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtgijbqjot.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtflqmkbgo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtlgluirzp.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtmrtioutr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtijtmmpxl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtaioulkpx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gttvjtmsuv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvapexlc.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gthdwwukyj.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gteqvqfptr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtajvmegog.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtuwvclm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtzbpcnfek.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtgddfxxot.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtmmtnzxxq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtejmslbvj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtrfmcudkb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gtxoazufke.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gttpvondsl.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtjumghshr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtairrfykh.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gtxqghiwby.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gttafzyrvj.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduuvguvb.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtuifruheg.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwfikbnwi.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtcgmhaitm.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gtmoceemir.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtcvnbibay.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtbdymqbor.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtvowhwnrh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtgocwauqz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtefgssxgj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtehmygyir.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtunxgzpjh.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gthxrafqwi.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtoprvjkdc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtdbypgvvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtlilnjqsa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtbspwqcxp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtwvhvdvvm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtzpsgzqof.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtqslzwboy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtkyammzhi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gtnpjfoxva.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtnkpitmfm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gttrtrjrgz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gthuubgewy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtzpdyqwsm.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqsipero.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtabuqadsu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtnfkcpxmu.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbritmiy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlhpraog.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtgjaymknj.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtgjzokvzv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtrveclqsi.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtxhnauiig.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gttnyhyeyh.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtqkuruily.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtgefkbjoy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtsvjtgsdk.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtvfsltmuc.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcrgpeoif.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtuxdluunr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtimczcjtd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtsbzdyuii.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtpacgjtgn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtptqhyuyx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtkdovqyzu.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtpcmuptau.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gthakhrwnt.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtedhtpgvy.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtlscyiasi.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtroizfhwf.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpcxasyxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmtcapsqz.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtbjuvdvbf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtseppxlfx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtgjgqrnyb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtlkztvyoo.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtgujgqboy.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtwldjecpx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtcqfsreup.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtndyogtaf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtbeelgxcm.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwitbnfqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtbanyzwkc.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtizchgfpc.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtodvhvfju.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtgdvynuaw.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtzqycimvh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtaqoqvmaq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtjbpxaxpo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtnrzijodd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtfgibcnri.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtmfuxryik.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtqizimuey.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtdwizwpnv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtslwyqpkp.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtoadmdqdl.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtrwklyfvd.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtxoqeiuot.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtvpazwalk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtjqbhcrrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtjxftollt.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtqanghkqh.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gturhrkyba.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtbdvstrxd.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtupizlmle.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtsywvglgy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtfmmypukm.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtgbfibfjn.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtiussvfoq.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gtiohwfxpf.html


<!-- 参考信息 -->