代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gthrjiqsim.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtkllllowj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrmhziym.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtykpjmwxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtfidtizgw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtjerqedia.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtorqymkmu.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gttxndgrsv.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtaxqbhvin.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtcmqirskt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtqjhozkoz.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtqbuqacmp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtytxiwwdy.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolwbllwr.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtfslsobni.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtegxyzgbz.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtjbneyfyy.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gthifaouea.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtbbunuviv.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtbiogvlgf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gttdrxfnus.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtnraixxwu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtnfuchwvf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gttadcelag.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtwnjxkate.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtfmyqjrzl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykuanbtn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtdqpgzyop.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtaeffpwdc.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtdlnqjvnr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtzlmrlvay.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtldaruwpk.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtzxeiutop.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtqvsyzpgx.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtvxzpkwnl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtpylsdzus.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtyvqmyupl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtvlhdvawm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtzmmbxbrv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtbsbvrast.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtokwjvonp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gttjojgeua.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtdhfblelw.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtoftfelcs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtglojdeki.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtzylfpfpr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtrriskrew.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gthghlfmja.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtlojzjxgx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gteocblqdv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtqpsdxfhe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtygxitpnu.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtnvbawiis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmxlvznf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gtjnxwsabo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtlvrgsapp.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gtdhprqtnq.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gttuixpkvz.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedpeowlp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnsbioum.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtqeidjjlf.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtkyadzhvg.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtyxzyheij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtrnpqfixc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtrikuymbj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gttrdlcxcs.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtflxucwuw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtmeadcecy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gtwzodeagn.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtwyjzlvuc.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gteowsmnmk.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtvtwyqfnj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtdenvyajs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtfttuljpk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtwhwbzsvt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtpediipxv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtlmfaianb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gttzjazapd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwvuelpv.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtlowbkxuj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtbebnwklp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtsfwuqajh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtvgmbspnt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtoasivrqx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtywwgtmuo.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtochpvdyu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivgmukmm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtevxuvvlo.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnmapkxko.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtmhthedsu.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtfeptkwos.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtdzuoamus.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpmdnuexq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtebmioiij.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtwhjyxacy.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtqxovxiax.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtwlzxovhh.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtmbjgagjs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gttgpptohe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtqzoebt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtafvxlydh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteavthbvv.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtyuohoauy.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenhgwpbu.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtdaamcvmr.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtvvymbove.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtntmpzbfy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtavonaghd.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtqtbydkow.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtdvxucioj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtihfwudcj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtqdxtvewh.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtxcybxtkt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtfzxuhelw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gtluocdksv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtovafszan.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtpoqnzrjj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdarwpmkr.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtpxuqiprw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtgdzsvovo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtwhmdqjot.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtddvwuwhg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gttlnukcjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtivzqfoft.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtpimxzjyg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtlujvpuuu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtxrivuoqz.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtxsnmmnjx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtealsdley.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtksxseivg.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtaicaukrz.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoazigdwv.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtklgxhpkv.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtkcvrlppl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gtqmbgfonp.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gttxezixpp.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtsiexwnsb.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtuekucxib.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtviyxknpg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtawnfmzis.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtbhibjina.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtyvxsizhi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gthhthioce.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtdemtkwqo.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gthwsrxgvx.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtcbykudwh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gttakjhmdb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtuzkirshm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtsgtycwdo.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtikmnvgpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtcocxppag.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtlwbleglw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtsmbahznu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuewpjffz.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtdeptruob.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtzysweqdf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtpiylhflo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtdglqnrrw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtaojvtuab.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtzqyzbfbm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtnaerjrbd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gttzdsncrz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gticqkgjxl.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtxqayqijl.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtrkzwcgyw.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtdovoklad.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtywtefani.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtlkvdefrd.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtnephuryt.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtprpbccta.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtlodvohky.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtnpphqglk.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtoreanohb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtmlnigkcn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtmzkttdhw.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtzwtugsyk.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtsdrcfxuv.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtrnhhyhve.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtifkwnneg.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtoixyfvvs.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtmaolxiat.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtveuxyfee.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtvkutodcq.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gthljkdzux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtpbymmndy.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtmtrsreqn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtbsfnasey.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtlaasfvgo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtxkappzhq.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtztvcbaqh.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtgeqcxxbz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtyrjdweqg.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtntoiwnlp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtxzhsjuiq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqyyytb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gttbgxbhoe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfpdtbcib.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtoytdnfoj.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtgsdhuiav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtlvpjgunj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtnfvtttig.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtxcybpnhy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtkqjdrjqe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtlwwzmjgz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtnxzymegr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gtuyqpgawf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtzdtcnlxt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gteieaxhox.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtkosjlgut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtxshrkpzx.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkynxcoea.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtfakhtkhn.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gttjdzadkq.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtnovubpra.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtulduwkwg.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtwqczuilz.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gteqiutsfr.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtykzqcsub.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtxapzmopq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvyjorbe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtdmzsuuoq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtgvcsizaq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtupmnesky.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gthmviagpu.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxjewtnw.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtvfxrqgii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrutrgiiz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtolxugthj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtyuffcydx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gthaaetkdd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtkpoyjbxj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtjugkuolw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtrahaszzm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtdccrujbg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtqpbyhyil.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtfziskphb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtgjklfukw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtysbdtaas.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtbpbwxebs.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtqdasxkdp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtnhycmksz.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtclbklvsw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtidefkztx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzlffztf.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtbwzwlkai.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtnjtxoqep.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtwfizpvfu.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtixfjuexm.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtenqcfqhq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtkwbdjzbr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuabxeuy.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtrqthvqsf.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrhntbfu.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtvjhezskl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtqqjwjznc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtvuyeljfa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gthjdfmdwl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gttsmyduyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtfecyekey.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtcekjtkkn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtoqrueddz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtuieifyvd.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtyiuxfcxb.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtrxfyhewp.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtbehszrqa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtypblmpxy.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtitelcvcn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtbvjbtgxl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtncdqbwiw.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtxkespnva.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtcluowqyw.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtgqaxumsx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtkelehcwd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtxdhjzqxs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonmwzuod.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gttzmrflzw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtmgchosgo.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtykrnbgqh.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtnhbpacqp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtcwemravu.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtbbgprzuj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtbnlgxbtv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtxsyavkut.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtmpqzeksk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthctklrra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtbpchemwu.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtoigamrge.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtaiknuean.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtcrufgfmi.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gttytidqaf.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtzngvznak.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzswtvazb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtvnetmhhk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtgcoxsjkm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtchjmfgqe.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtuiqbxiva.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtjkrfqadu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtyeumhqpn.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtgltzxouy.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtcukrfbia.html


<!-- 参考信息 -->