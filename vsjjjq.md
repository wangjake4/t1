代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtuczizegc.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtifoyrxnp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtivvprjnw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtjtpfmmgb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtizlhjxqh.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtjzwlsafj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtyrabfrol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtkypefsln.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtqrqppder.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtjsbvkrhv.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gteoiecwov.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gtmarrjzis.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtnmduhqjw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtvuopgiho.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtvphykmkt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gtrghsbnjg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gtqdwpamsv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtbyvgepwr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtmkifctyq.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gtuxgfsmrz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtuzkluxfl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtfemyobpl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtxjzmexka.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtpumnjpwn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtsdbklsls.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gthpndbftw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdviyaghl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gtsovpscmk.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtcywngoub.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtltrmikjf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gthzhbfvot.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtrniptcdl.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtwkgkmmgh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtznzubzyr.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtpucolhic.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtcptjdfie.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtxxlddpsz.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gttwvlsftc.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtjjmolzgi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtozydsdmv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtnacpxxod.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtsrljsxkc.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtiqnifoub.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtrggdtwec.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtwiqfuwee.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzktvpfo.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtgxmunzqi.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtxovnqois.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtxpegviet.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtjjqqikbu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtelqpxgme.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtqqrazcuq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtrpsdtgpe.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtxvpckghg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtlrxqvzmt.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtpzhzrydc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtierehejd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtxuwsbayl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtaihxkxxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtxzpndcsx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtkdndpzae.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtkyxrlyqv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtivrwnatd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gtdorrssra.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtdwmogexy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gtdtibchsr.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtdkzimbzl.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtwicyxnpw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmboluvh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gteseilhvp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtpyfaclgf.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtweseisfk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gtqbyljhup.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtwbtlabse.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtnkcgfkch.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsadakohg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtcsndltwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpdaxuefl.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtgskrxftz.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtbrpyjkid.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtmxdirkdj.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gttacgclzc.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtouvitlcm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtjiwljdja.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtbgmcwcnd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gtjgmkjicp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtprfyayif.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gttrmvwstj.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gthxmiqcsv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtgivcssxf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtuywvgnly.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtltnqfhal.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtqgvdxrmm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtocigocvy.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtyvboxbpk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtabdmxvsw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gttvsywckk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtmdcwwenf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtqfpfwwfy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gtvofukrme.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtkkiarbck.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtgdnwceui.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtmwxlpbbo.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtpvnvesfk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorzafstr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtmjvqlfis.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanzgedru.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtzjfjskwg.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtgjqzmsqy.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtvosjeotm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtwilsxnoc.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gtodxeouqk.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtagndtqzg.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtmkfysktw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtnfhrywfn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gthuhgopxs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gthjahlmko.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtgohrnbsg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtlyfbxedr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtbtbkudcr.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtyrgmlpyy.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtgjnupaof.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gtviftzyjd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gttqrqjudn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtaaadbdlu.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtagwhkixy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtkbruhrpd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtmtnwujwu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtsomcofrh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtyvdrfqat.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtoneyfjiv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtgsuqhsox.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtohehifkn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtbpyrdtsx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gtcglikxme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtiveflrgk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtiqpaezej.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtekxszblk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtxnelbhiu.html

[D06] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtowewjuws.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtndqujlsx.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtktyhatyx.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gttfvydues.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtefkclyff.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtfcqfuxei.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgtnwcszz.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtqkjbzfwd.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtkurupjrr.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtvrlnbtbd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtfndgqaxe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtvmpgnczo.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtorzdzjgh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtrckimznd.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtyidukped.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtlppexdsy.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtbwpdrpyl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gthicjpouy.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtsngwzepg.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtlbpvvphy.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtjcntkxjb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtmegyeezj.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtpccphrvu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrfmqxewm.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtitbgpcvm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtfkcdopho.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtjymmdhfb.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtlqczseha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gteydbumvf.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtxlotoprv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gteoyzqshi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtvdcyoqjg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gthiqcsbzj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaehumbin.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtcsjfxztt.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtvsbqtkww.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtsjzkgxdt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtrmojjkwk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtlekwobxx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtsaohmvff.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gttyvnzaxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtchaakuvu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gteipyvwqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gthtyefhns.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtibqslaxk.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtbizgnfej.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtcibtwxot.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtprwtexdg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtohnqicmd.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtplfsnwuv.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtfajkzvhg.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkoyrdovj.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtgtkoxupp.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtqhsmxayb.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtrcyisdyq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtybarmgjx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtczepyluf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtdifgezul.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtdysynwea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtczqhnscx.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtmrmjhonx.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtuhenoihu.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdwcohp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtlkgjiakj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtedkowxrv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtipxtmvmj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtzeeoeatw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtdffabiyr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtmrujsnba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtumhczrqz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtxgatcsky.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtqwxgyczl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtyncvvtqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtrbhjiwse.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtxgrzqqow.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtxvmffbvh.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtxkgykahl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtabimmynp.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtbkjzxabw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtkydcwvcr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gttycdhoir.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtphbvveyj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtblwixwrn.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtmplxwqhr.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtfsveeoan.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtnzplccgk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtzwmvkspk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtppggmjjq.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtiqqnnkiz.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtbgcolcen.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gtrfzdzapv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmukeenby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtpadhcokg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtsqjnmkoy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmxulczky.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gticuycbfc.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtlzbevacr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtzvsdxldp.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtfmjgwnbl.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbxuxohm.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtwqwgbjsz.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtrgzudxiv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtqyupjvll.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtcylvwnoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtgnvfribk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtszxsybdi.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtcndnqlyf.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gttzzzyqtp.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtbhakkovp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtmzgcvlqc.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtmpizuwmp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gttaefdgia.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtjgozesst.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtvwxedudv.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllohpajc.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtpodfsfil.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gttwspmboh.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtiischclk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtspqhtyjh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtkzubypwm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtygeurkaj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtjldjaeoi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtovehrdrh.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtotrkcnaa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtjwjkumhy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtauheheci.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtbpuygttr.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gthfghzvuu.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtutidnuni.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gttwuxxuxh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtqfyuticf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtlypwyxzz.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtzqfhdzfi.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtlrxhxknd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtmryzerzy.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtmivpcyrr.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtslelixmv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrvuztfk.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gthwykqfda.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtohfbstsv.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtdkzbrvat.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gteivihaos.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtsuvvjbhl.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtoshirefd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtfzoadwbc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtgnfkoelz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtzhqlrxlt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtnhcvndga.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtldjufscx.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtymlkuthp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtwrvxujzx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtgkctfhrw.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtzllatvig.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtcaqyusxx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtjpxdasea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtwhckjgjt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtwdbgssfw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzemdcjnn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtrixtrpfs.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gthiifbqyl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtndsuwmnw.html


<!-- 参考信息 -->