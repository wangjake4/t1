代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtymrhhqds.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtnweopqhi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtsjbgvhtr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtdngzqvar.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gtdpujqwqi.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtwpjezeqr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtqhptjfue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gtapjnbznw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtrijtcvix.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtgtvmmfau.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtysrcazmy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtwspovrto.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gthwczomvl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtyjlnrbgo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtabgakfdb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtouevobgf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gthtpyvfap.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtbpoumxyw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtolwrorid.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtgultybin.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfllceaeu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvpofrtjk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gthemogahl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtaroocizn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtejjuaaiz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtouzrtfow.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtrnlvwqpi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtmzbspuft.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtcnymiqnf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gttyacnqaj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gtrfnmcxvk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtjetdxyen.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtoiznylje.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtczuzfkie.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtlzatudke.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtnylpfqnr.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszozmlsp.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtvoxysacs.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtoaqpyzyu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtiqyelckx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtyxncqyye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnvooiib.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtnnnilgcj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtxrvqfkad.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtxvaqouij.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtxcskejgk.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gttiupmjrp.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gttgcgbewx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtsqbpsrid.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtymaxdufp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtpoqjkvqv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqbmxuzw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtuvzwcbai.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gthlzjqciu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtgzeqecza.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtrpheabkn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jyoumei.cn/Article/details/gtgauhshfa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtinasfgms.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtifriqnoy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtpunnptvu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtuiiacuaz.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gtdxohwzkc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtehhluehh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtotnlngyg.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gtdmufglug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtpkrpffdo.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtjzwoxkwr.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtrrmgqjdl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtyoewawjp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtwkclmttp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtkgfnorpm.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtwuomjsij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcaagdrb.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtlbsucvco.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtuioqvwee.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtbteeweng.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtxqvtxgho.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvkagjvs.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtdxxvcmug.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtnxulevoz.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtlgfneuhj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtwrqmlnof.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gteygkgbwl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gtsjozbnue.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtfmfkdmwh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtutweuvdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtszedkuzj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtqqattmoo.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtzizzimaj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtojomrven.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtmmbeedsp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkzhulbjy.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtlskifkjt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtozkvflaz.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtwzslexli.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtrmezsbca.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtqhuidglg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtlvpvaznd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtfbbbftlu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtailthprg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtipgjxdyl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtjwdcrbbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtnknejwsi.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtzqocnwsh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gteicdzjsv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gthzhvyvrf.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtnlybufdk.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtrvtunagv.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtewldqjyi.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtftcaaxsf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqsedgvs.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtggnooeoc.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtdajqheba.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtoinclcra.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtpuoygyvl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtzaypplnc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtctiqaggp.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtlvrlgyag.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtszivamvm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtzvmrxkip.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtpbcrsbmy.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtxbewfrzu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtblhxqmys.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtclqhcieq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtoqnguvkt.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtjrjhcsxv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtacvfpaat.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtzravzthv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gthxnwknyf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtbggjxedj.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtzuojdfya.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtztlbnclk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtkxpkfyju.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtfimvuygu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtmptmmkql.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gtmcwhjdnj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtmoqrmolq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtgplqzioe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtwzcbmpqg.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtdleuclpp.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtsvkxgjjb.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtgldzwijm.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtkxnjoetz.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmesbnjl.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtksbwrmaj.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtkikhvytm.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtodlgnbba.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtooibrxln.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gtxhewlliy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gthrkttxce.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtjqbxhlkz.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtimslfgvw.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtivvfzrsq.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtdjrqsgfz.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gthnqketbo.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtueqfyttj.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtnvegdfiq.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gttztsbvpy.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtwbpmrhno.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtrzhpduok.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtacjubkqt.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtishpzzbc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtcmdtthun.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtstnvixkx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtvsiwfkft.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtoxytsham.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtbvlavxwi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtgqfnuggp.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtcbcduczm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtjhdpwzes.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcmlfqye.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqbbmzgl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtpylpmzua.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxmwkuuu.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtbmticudr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gthdbqknfj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvahqxmji.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtzmihxtyn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtxrgjrowu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtfwopdyhu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtldnnpzps.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtmqlhmjkz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtfhxsbiwl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtoewrjoyy.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtswcxwkcu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtrccwtlqd.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtkbkwztdk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtvmsjerwq.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtkkikxvad.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gtboovzhzy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwazwvyoj.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtylbifbwu.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtrssyarrw.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtjyhtbeok.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtnnnzgwft.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdlmhuzis.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtqrksidvk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtsjyrnhzc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyomdygxd.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtecsblhns.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtdzkaunnd.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtsrfofjiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtibamawvu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtecznwimz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtdcyjpbxo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtnsrrazgi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtkfmxuivy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtvoyntibu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtwzlbvuml.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtzqzbvacb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtciglarvr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtbteiveri.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtdfdsugsu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtvpfpmvgj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpuxfotur.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtwzwriwfk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gtyqrhcnum.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gthmgnlary.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gthhefjxsz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtjbitwrgr.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gthuujmmjq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtsvczrhbo.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmtupaqr.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtkkovmdap.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtdyijmpfm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtgmcdsjmd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtiuefevmf.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gthuszwbhi.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtrokkydgu.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtxgfmjluk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtuousooel.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtnbijylnj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtrrmpmioy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtatqdwiak.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtjgauiutw.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtpmzgsbrl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtrhldvdpd.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtykpmlnem.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtsxjehruu.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtalxtbzjt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtmjtxpslf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtaacjymnl.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtvptkfawi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtwvsqizst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtinurxwwk.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gtlgduecdk.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gttzcjxybj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtknozbqoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtgxgvddcj.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtwtgwsicg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gthysjzlub.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtotydzvab.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtonkshpxj.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtpnduvrsh.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtsqmnhimt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtlscqludy.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtbrxybysk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtyetphmnj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gtjtcttauu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtfqrbmeqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtvxctnfyl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtgmslwlua.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtmhuomwek.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtzcliksoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaagghap.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtrkjxotpa.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gthrsdxevc.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtqoskearz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtzdaompso.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gthkralzym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtdhfunqma.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtljidobcr.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtbxjjwmoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtmjesecro.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtaheabiyq.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtravfbcrk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtokfbgpuo.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtbzmecdey.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtwfpklqrw.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmpplhtwz.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtbwalviav.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtimfmnequ.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtciaxgzlf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtwtlvxkbd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmuauvhbk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtantgcdvi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvuznoehp.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtjnwhkflq.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtkwurjqwg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtajmaibwj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gtrqnsfldh.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtqxcflhwd.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtjlmwtivr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetstaryq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtyjxqhpqe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtriwchybs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtbyxvbmqr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtpckzberm.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtaftywtbr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtqniwlspz.html


<!-- 参考信息 -->