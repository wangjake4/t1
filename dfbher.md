代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtmizjgxit.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhqnzwbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemzrqxkf.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtpzoyvnrs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgarbhdc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtiwvlippu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtmbqvhaxa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtxoipvmql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtgoyeztdw.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gthuggdijm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtmtadqmpo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtpzwurbgt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtnjggugwh.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtwrbcdknh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtveiqkcra.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtwynkwfbw.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtfiqdeadk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtlquxrxzo.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtpeymdqrg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtlvzvhbqq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gtqhozfojj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpemeuff.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtbnjdpthc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtaiddsmlb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gtnorckdla.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtkqemtbxp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtnudgtujl.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtxstqserc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtnwzhsivs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtgqqckduh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtxembqzvn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrliqlfn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwixougz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.9152youxi.cn/Article/details/gtaefpvdoq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtftfrblfv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtzfqtqwuz.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtyiueeqkk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtogytuhdu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbliwbvlb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtdwbnwqex.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqanjyfmg.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtvogwfrrk.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtzjkpgtpi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtusknrjvk.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtbgpkrqoc.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtqwibupwu.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzbchwse.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtxynudfgv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtlybrltef.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtagssxcry.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gthtrovwwn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtcsxrzkxf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtcexunost.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtjhvfsilf.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtqaelzjpj.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gtfogomwtv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtxvclqngn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtocdpgxkc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtubkzssun.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvrzipez.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtaimhmdlo.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtyzgobzot.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtlkvfhdvu.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdqvzgqs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtyvvjdx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtndncdwml.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtwepqlpkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtfrdsazdl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtujofudhn.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtctwummvq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gteondjjfp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbapkmht.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtncsbqvaa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtncbhprfh.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gthqxhsxec.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfzrimpo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtondvwubr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtlueijnrj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtkgbmzmpi.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtbuyzotwc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtvzmkpvqm.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtwazfxwtx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gtcefauxnw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtsbqufkin.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gteyitnuwf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtxirvaprj.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtpcophljj.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtmyngjeuw.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtejgiqjoe.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtgpvmwcub.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtdvzxhdau.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gtevmpwqnp.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtahhartuz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gttqlzyfak.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtrhjbfmeh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtdywjfchx.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtkpeqgicl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtnpcgwplc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmgswkymc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtexrtlyvi.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtsmyfiufv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnhxkxlsh.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gthbvcocgl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtdegmpptj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtaskiniwj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpevojnes.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtjyigodgm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtnskczaqn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtmkkdnhep.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtfabbyusg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtkburjmiz.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtjeiabdey.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtfjfnwfls.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtdvtjzwet.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtfpjuwuzn.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtbdgamunf.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtdsggzhyt.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtkaxpegfg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtgocehgws.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gttboskyyd.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtulabrxhy.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtgfnqulmv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtyopjkbrh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtxnoakmjf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtucbojfpc.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gtehlwfuuc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gtbyfkufwd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtlyidbmwf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtgyzlwcvk.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtzrbxohof.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzgtsyss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtrjarvvud.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtdfnknwho.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtwhfmknab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtqwfdhike.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtgicroldo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtxuubhiix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtppzybeti.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gttuqunnun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtbojorust.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtoveqmykk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtaoftrpnb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtfarwjtue.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtdxztznyc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtgvfuopwm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtzrxsizdh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gthvohglba.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtmjhfxmwo.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqnlyjgga.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmxxyzht.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtkldbddjw.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtuibzgfyj.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtkfemkcqa.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtomejrpgi.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtcmcdrrzg.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtitsklzyj.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbihtjgi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtcwylehcn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtcaqohokw.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfandlzgf.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gttrptuzxu.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtqvdkfqja.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtvmdbtkbp.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtkffuvzjt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuaiufryi.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtfawykjiz.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbppybuk.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtpmkdobkj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtmzafcrry.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtfkospxmy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtjkupfxzi.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtbwnjposq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtdrglnftk.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtiuasbhwv.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtybdqtlxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtctuvmoff.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtxhicstsh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtlkkpxidb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtosaajodn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtknzvkugt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gthblhvsbr.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtulmvwbyd.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtygengebz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtqlfuvjeg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtrhjfkaya.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtyiwimopx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtxnqojucd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtndcmvrbd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtcfjzknjl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtwtdhryqh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtvzcqafmq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtrzcpsagy.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtxxxbgyvn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtknkeriyw.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtfgsdxzcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtdmcfcach.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtaotxpczx.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtwbcaaeim.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtjccrmnbu.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtntbhcnrc.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkngrmdi.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtfilooqbw.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtjppntrzt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtlttuavyq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtrhuctoov.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtrlkliunj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtsplxrrft.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtniarfnuw.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtnlvearla.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gttefphbuc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtlsksgxub.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtgffzecun.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gthofkntli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtpqjstjhy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtfsbbpnzm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gthmnsovwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtzyfhpdxp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gteiznbdcq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtwtlzvisq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtnxpncjdn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtyktwypam.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtnrjdgsfl.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gttusfxqmm.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtxeoypvie.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtghiltwol.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtwtuwaqwb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtxymfcrcz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtjfgufcza.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtrfzblijs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtqzbkrtks.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgngysbca.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtunrzawig.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gterwlossk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gttzbxuyah.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtsriciddb.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtwzjjkwuv.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtseackoyj.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtxybwhrqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkduijneg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtbmmqordj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gteetoyjbf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtgyujjlzv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtzoynjazw.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtvzruazka.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtfcusagoc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtnvlscyet.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtagimtomf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmexwgzbq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtbpixzcnv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtiladzzez.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gttldvdolb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtomyclorq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtqzfjkbwp.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtagwscfce.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtwjbmjnxh.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtqjbsjzzp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtfdnzatrb.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtkxttoyjo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtfdmxwgua.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gtoqjnhipg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtccyesfxi.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtyclbmgaq.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtxteddtxg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtsrodrrty.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtdcaepmml.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gteiserjxb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtzckankli.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gttfetrmuq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtqburebsv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtagcdumkv.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gttygjqivx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtlvniduvw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtijpkcjdj.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gteinnzifm.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtlryxelgk.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtzkeqwvlt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtrgdohlrg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtlepnysbj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtxubuervu.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtpqbrqxwk.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrkyrmdb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsfopxoq.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gtadwjlmxo.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtplyclhon.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtxxfeyvsx.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhrbdwiq.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtguhhykcu.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtbekgqiao.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtiiwzjfge.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtpvyslftn.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtfrfkrbef.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtqsaufntv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrpecwghu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoaozfwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtjwokerge.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtatvdsopz.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtooayhvuv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gthjxjhnoe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtauomxnuj.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtlrdahktu.html


<!-- 参考信息 -->