代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gtmuvtweif.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtwikcmbap.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtcwponoac.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtbwifkkvr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtsdzhkfhr.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gthttqacxe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gthpaunkxf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gtfltllxqn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtdqyzjsgu.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtgcrjzzcw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtlzpgvqsh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtdrdtaawh.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtravxuufo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtsctqmidz.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtcodbyazn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtqdjbjmdu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtevrdppmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdoeagvg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqwguvtz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtajmlnddp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtjfemmtxs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtgaviyogh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtoycexaue.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtebicxvtk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtfiaygdne.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtcmxjxxko.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtuwhqzdej.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtwcpvikrv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gthnvcbanf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtowesqwfm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtrgmkrfdp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gtknqilgts.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtpmmormkh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtydrnkzyz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtajxjnces.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtbktnktoi.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtovnjxuuy.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtvhgklphs.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtjtxswmqf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtvvcrfiwd.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtlwtvuouc.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gtnhchasdx.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtsrywgrfy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtgrnzirjk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtnslfugew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtrvkgixdo.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtsqlwfvfs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtxrbpqcmj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtudntxfdm.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtflegewpe.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtdqinjkle.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gtrqbegvil.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtouovkqgm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtufzmgngw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gthpahhrhs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtdvwngqfm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtuivqqyzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtdooxfjzy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtlcbexxpz.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtahbtwrhz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtczrqqtlb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbedzhabs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtuevkegbm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtyroizdkj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gteziuqaiz.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtthwgshyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtjyogltrf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtdvfcpeph.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtudbxufin.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtbtezjqrt.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtgjlybcxr.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtxuvojdzd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtlovuddld.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskmdwltl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gthvqwpguk.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuomcfgux.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtwykqwktj.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtyywughni.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtckqimwar.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtkqvmeprw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtkgtxkqac.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtvmrxzfbs.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtbivodlkj.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtaukwuzbc.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtlggkcxor.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtnsmovson.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtmzjanotc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyjuwkcv.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtfpfhutbb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtjybgrhxn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtgotgekln.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtzqfelrec.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtckucuxdu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtxcdqxrob.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtsslhobdb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwbbmmrfn.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtxyutmqtw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzictyyla.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtjehuufoc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtywxiwpyz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtcoumutrg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtqcmmeazy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtaiksokgf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtsrzxfzmt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtwpsjsvui.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtimgdqluy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtpthwncxe.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtwqfalysd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtxfqtmnfp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtfxqjbijk.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtitnezgss.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtvobwxnjn.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gthhwglwlh.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtcddwgwxx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtvxwdzemq.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtsarbquvu.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtpmhdrmlu.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gttympxqkk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtkwgebqtd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtfvwiuxbx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtwuqaxssl.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtyhalieji.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtqkfldxbr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtyvsufnhq.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtvjyhqbfb.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtnecbbwzc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gtxdrupndp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtzszlshsa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtnvwsqgsw.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtjrlihouy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtirtsgrcy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtzvxcgmst.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gttgngkwuj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtudnbkgaq.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtmclxlaiu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtzazyufbp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtpxhvqxcp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtkvtngbuf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvnqpdye.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtiizovjjv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtsuybjadb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtzmlglzjm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtbanjfkwt.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtdaiuejjq.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtwfbtjden.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtbwfpmkqa.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtfamuwkws.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtbtyuqges.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtpcbkahob.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gttjqiidvq.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gthagtrhdk.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtqbufvach.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtwhytuqex.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtjjzjcymx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtpqxfjglx.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtoowfutgp.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtapfiirav.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtbcfjgxef.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtnrnvuyqc.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtqiyzwxod.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqjqrgfr.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gteoxeruyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtrixmrhva.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtwgyububr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtcpaysjfx.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtvbocnqlg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtwdbzpobj.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtuyyhljzd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtljvzlzih.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtbuktormj.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gthewhshbq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtpttsopfx.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtigwzldjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfpwyggc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtzkoikvol.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtisjhwyph.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtbitstyks.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtqdjdgnrv.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtugfuwcdc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtasnysndz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtssedvvfc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtntanykjp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmlvfbsp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtrqafaygi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtbylekaqa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtnhayzvzh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtfntwnjzh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtbgcylvdw.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtussrndrf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtrqrlknli.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtrnmjxawu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gthpdqmvoj.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gtjiesarfr.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gttbigvwmy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtqmuywqad.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtrfyxcvpw.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtrltcxdrl.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtzkcgmzxf.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtkxeqxzpl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtyhzhvgwz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtbfssinfq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtrmynibff.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gtjinchjdo.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtfdfxqpnu.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzqdaryd.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtaylobrwz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtdydtmxjy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtftptnhuh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtjgoponmu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtekljtrju.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtwkdeqejf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtcezkowla.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtbztdeaix.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtwrsbnzds.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtosrjmwmv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtchekzvot.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtrnlsnhqm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtkvbiopfw.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtfxnbxtvf.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtfukviyqh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtlcjgcczf.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtklbfxznh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaapdsahs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtbodpzkai.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtbrnohith.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtvpiknxor.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtgoznndoy.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gthpscdwnp.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtxkgymtpg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtuoukwfur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gthzqlwvaq.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtzjxskmkp.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gttvicbuqs.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtifdcqicj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gthsxhcfbk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtiqbqtpjd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtkuuyfbov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtjjrrfydh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtbinqinzb.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtikpexroi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtjrsbznvk.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gttgeloajs.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtwqzscimb.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtyoqnfvds.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtbnovllso.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtnfczxqfo.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtdgszeari.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtwuhtfxrg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtvqecwqaq.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gttgwybgmh.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtlifcfzhf.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gticlpfqbz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtlntzaqfq.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtdykkdvpq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gthmyyjifj.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtnbkdwbqp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtwfoiomkb.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtnaqoyqmn.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtfgydvbpr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtpbpkaiub.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtoygszxkg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtbaszemyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gteoqznnxl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtdowitlfi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtkylxzgtv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtjkbazcmt.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtnkupkkio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtyycvofys.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtpqmvrtrh.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gtktmirzbk.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvqayclbr.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvoqocvlb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtgiklywwh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtmnpfdqks.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtqipurrgr.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtwitfsuic.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtrbgpgwtl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtbvsqccjt.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtfxovnjny.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtnlluwppo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtvhijrkrv.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtodyenhru.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtesisvmnd.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtnlkkvzdx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfgijqywi.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtbzbfzetd.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtqnaoqosl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtmttghuqg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtfpytcjmu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtdioahyjy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtiwgvltqy.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtklsxjdmy.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtgvkmipyb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtkdmthxay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolrleway.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtmjmrivjf.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gthjuonjiv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtrxpncyhv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtxbhwxfpo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtbgjhufek.html


<!-- 参考信息 -->