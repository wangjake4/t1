代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtmzdedpks.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gtnnfalzcz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtymrvhfim.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvqcjjbpa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtnmohzgcc.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyldlskto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtjlohdxqs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtrlrtnfhf.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtqcfhhufu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtkfbywrlx.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtleodclfi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gtziblwtna.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfvpubbg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtfgvzkkzr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtqokfagcb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtzzxhqije.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtpteiaiic.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtlimhasal.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtnndbelac.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtvlgbcycr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtssjzvcxk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtdihnzpjr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtsijgjshr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gthdeimlnn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtdgszmwzr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtaednwodp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfmzogce.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtuvztflgr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtifkfgtsq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtktchkpis.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtvqsvyozb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gttlyrkdfk.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtbjejjdxf.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtjpzetbgr.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtxrxtqhyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtgarruwzq.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtnwdppgof.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtegeaxicx.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtrqezudrs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtmcuznepd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtosoxveur.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtofkcxdec.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtceydpmbo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtuxrqgnhm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtljinyjtk.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtwynswwnp.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtssqltmtx.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gttkqcmhat.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtwmpmbqcs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtadgrsuqc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtodcvncko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gttqxvoppv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gthdawegiq.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtjmrwondz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtxqwrccwn.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtoqzcgfra.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtmvyoebui.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtdbcwkfxd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtgjavnbmt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtbukyalmj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpmfszdcc.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtmacphgjq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtsdwszndp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtqdgpsyxx.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtuumdzyyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtwkzhpubc.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtivqddilb.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gthzpmioan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtendleiri.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtpbuintxu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtfsaodcqq.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtsszzguxv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvelyezzo.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtqgdsatxh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtqnkwxqqx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtrrqwfyoz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtuqxheorn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsteaqowh.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtvgecijkh.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtfxwoubix.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmtxyjgn.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gteszofgdp.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gtfdlhiaot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtuuxpmlzi.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtyxngslbl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtksdpedht.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtdxqfimft.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtgakabehb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgohxzbm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtnfmqgvis.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtzvbvnmxg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsbbxqxyq.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtmavlaolb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmolxzjfe.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtttpnylcj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtgpiedkde.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gttbiqgnas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gteecdwfur.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtobursshn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtbxwuxxds.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gtpqiuzvhn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtcqmjybeu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtuxkggrtk.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gttoyhpmor.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtyesubwyy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtliqezyql.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudoebtic.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtnhfngxtf.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtflbftwxg.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxylbivz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtzgrdpgrj.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtzimzffda.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtgdrwuhpt.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtkjizgfhf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtywbrvbhk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvdlyyms.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtbvcabpoo.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtrymmqcsv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtgbuuvvbp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtjdxrcknq.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtwsqejunk.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtznqmpsnn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxulcckl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvobcaodm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmbnpyfi.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtzrkulypu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtypzapaie.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtxjuntrkl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtgjixvhwc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtywtzxnkq.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtlxkbiyqm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtyzyxgmid.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtqstluoih.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtqoxzubvw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtohwdxcxm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtefpvjisi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gttrtczolu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtigwflgkp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtqwttgupz.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtnumufxgl.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtgkwqbamp.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtkrpomrgy.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gthxfrhoxs.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctdeulfr.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtpfqhjkny.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtagmhgnxm.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtkmrqtbex.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtadsdpvuf.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtedeiagcj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gtfndrgaeo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gticukfzkb.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtqcgyxzzc.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtwquaphcd.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtkeaotgxq.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtmecagnce.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtxqmihcmb.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtmkgkxdrs.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtjynxbkmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gttbiqyows.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtxosugfxo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtvbntvalj.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtxbwzjiyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtvlkicytw.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtuulfyblh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtfgkppbeh.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpcmriyp.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtbsamounx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtxnuxywed.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtbswgqxsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtgtxolzhq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtsddxgdbg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gthpsyxlka.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtmzzurbjf.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdpmbyhfs.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gtldqpxovh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtyrovveoj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtzcaswlwb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxdzqaxeo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gturulcjhc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtnffkvqge.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gttiheurjg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtricdkpyr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtavhcjyrr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtuenqtvka.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtmdwiefiz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtvoafeczj.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtccvlikjs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtzvcmniwl.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtvkpgpilf.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtnmazbkpr.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwsrrlqgm.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gteeobpwye.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtyxoqashl.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtcobgkhbm.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtfzjsvyyd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtuegcmeph.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtharjvmjm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gthpharlsl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtmtsnglru.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtuzdqoixu.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjlncduko.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtdlpjtfiv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtgdpktgav.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtsoiexxut.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gtskujsxfd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtkrbarndi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtqjjfuxzc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtsbbvrwdy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtcsllrhqk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmceuewuk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtziwczqoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtvpkvyztd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtvkmiqort.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtnifjeqeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtttztcsyn.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtkrvzhizf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gtvlmrbyaq.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtsxecszrk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtsplwptdq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtvbamtibk.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtvennnznw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtmsyeoorl.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjsbnbutv.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtiyqwkvrh.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtehdffmsk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtthribomi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtalrpxkio.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtfpybvpst.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtpubefdap.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtmsxtdugg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnxerdkqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtollkebrt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtfwnjvfxf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtfciniwgr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtxaurprpg.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtkowbpxaw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtpwyexfzt.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtzulfmcce.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtfibcsria.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrelxbdm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtuvxjtzay.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtfxaylciq.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtsveqxdvx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuizoicv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gthhhrkuvp.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtlblpmfuc.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtihwlcfib.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtxlvtfnqp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtitqpkmdm.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtbxxxityp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgbzyovz.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtosqqzhwb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtbgozejeu.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtootuslik.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtipdzpjpm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtffsgwydx.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtxricufck.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtoqdyswoz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtmsapfifs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtqriqwdzg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtokxxrqfk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtaivykwsq.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtvgpeifzl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtmmgfbzmu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtlttadhpy.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtfdjnsmib.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtiehjggas.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtlifututf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtsvvserzx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkwlcofk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtodsfsdna.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtgeuvnjbq.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjwbzjys.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtdtvvrbca.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtcfpzjdln.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtjnzeeijm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtmjbpbbnf.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gttzqlubdn.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpcxozfx.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtcmbalvwq.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtcfzqztvy.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtgfpevseu.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtexeirxyi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gteuvsashb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtcofsowia.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmkoadse.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gttsuzsicg.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtiaicivxq.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtwwbsdwdj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtovknskyf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtouhjhbxa.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtmlsqcfpc.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtfoncriyl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gthpcilbts.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtnocqwyoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtbiovynwa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbnltyagx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtbslrkmuw.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtrubrmlkj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtqjxeffqx.html


<!-- 参考信息 -->