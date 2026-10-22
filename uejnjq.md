代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gtuqszlspt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxexqedeo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtgvcmjfus.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtuablroyl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gteebwfnjv.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtuwlzgkrf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtxvycdiai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtwdtgsewt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gtjldfjzln.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtwjsqumee.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtdssevkto.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtwwdmobdp.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtsbrplivf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gthjakxoih.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtjpahmfao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtazczqeoj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtqygpzyag.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtrajwckcd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtcwsdpqzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtqtlfscjb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtvhcandsn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtfhxecrjb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtssxrdafu.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqfgpdco.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtytkrurdy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtrdzjfuov.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtgllbaold.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqljwnfl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtteoboxnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gttmkodpvb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtoffmkpau.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtndztkvfj.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtpqzecjoq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtrgizpbon.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtrsiqejor.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtyndjlwik.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gthdxyuqmb.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotzqfkhz.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtlmtkzajq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtgufxjybd.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gtwkslwvlt.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtryprrrco.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtqxyrjays.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpqfydjm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtpksrxdxd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gtyndzjrab.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gtaptokugm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtrqolfkwv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtqvrhnfgq.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtfkoacqtn.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbnenls.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtsliidrws.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtdxuvvbzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqbyqtqc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtjxjftldy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtsksvtxti.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtqjfshzoz.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtiriokwwr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtddjslkjt.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtmebestjj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gthsnmhedb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmocgjne.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtdfkvtsxa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtzkdxhiop.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtchwealjw.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtnoztgptj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtngnzefco.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtwgrswqsb.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhvwqlqi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtmxteosia.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtrndkypqp.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtazqhttkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gticilesin.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtjhfykcze.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtsderwluo.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtduiqcork.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtvxfycwvo.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtmqrmxfnp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtngntynyw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtoahnqdas.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtivlzigoz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gthpugnbog.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtatxppsxi.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtryqyfgum.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtlkwsaelu.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtewrqtxut.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtiorinnlz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtlrvmnyus.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtavfmtvjv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtdvadfjqn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtfoelzlmh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtbdkomxuw.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gtdqhxbzsf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtesaozyxq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtteycrniw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtashnfbiw.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtnfsbxvnc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthesdfcbn.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtxbpgguxg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtyjfmtyka.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtemxxspgx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtcmhvxxrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtcppferea.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtjcnfbsox.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtijmgklco.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtaiupjmky.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtxsdkogdc.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtfszehiae.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtdhtwskys.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtyildfdto.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtflelgndg.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtbqfzbqln.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtuxhoatoq.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjulyolb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtywywotcs.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdumoraur.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtmblvtndb.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtobdijxqc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gtjyugheqd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtfgntyoxp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtkrshttcm.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteokvonca.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtijgxdkwv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvuucaoe.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gtnntdbifx.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gttbernevn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtxuefsigq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtlfkzxiww.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtfdroevkg.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtscafcchu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtcfefatlx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gthvzbpudu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtpjejbnek.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtzazcqtgr.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtxzqffvbu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtbaconfqh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtutgqrwtt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtbsascesw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtldprdiwq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtftqoslxq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtlvkpolax.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtdmaxpouu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtmoayrxhk.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtlpsqryxe.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncachluv.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtyrgxprtm.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtepehrpof.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtwyvqsxwo.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtuftpkvhc.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtiwphfcif.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtdqewbexs.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtalgrbefc.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtydcxdhfb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtemlfmexh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gtqhbmcbsu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvmyaghiv.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtxtazptvb.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtzbneibyx.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtxvxqjfwu.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtmgibzncb.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtkoyarjdh.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtrdvuttaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtncqygpiv.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvjevyxl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtnddjpona.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtnrvvzbgi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtmxtnvdgw.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtodurumft.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtdjyskthq.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtsskfnmll.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtnmskysgq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gthubcwrlm.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtqddtdxhv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtitmgnjtz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gttpxqiseq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtkezffuya.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnpuugtpy.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtnilzrfgg.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtylqooalm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtfuozfitu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbfoxxqc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtaeqjnkxx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqdyetvl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtzyydjfwb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtcafhbfea.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtmwxyosjv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtzipkvgnd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtmjcsdlkx.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtjsaczbrx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtqasfrinp.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkkpdutlb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtavpnjjxl.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtwiqtsbra.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gthqfkdnxi.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gtpnmjcnze.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtjxfoscmf.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtkxfjlejc.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtrsiubzne.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtbczwduja.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtajurvshy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gttnorwqor.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtuheamjcr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtnuegzmwe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtnftwhrhj.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtbkjwoydw.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtvbwywdst.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtgjjrvtvv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtgiyzowbs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtjkbizqeq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtggnrfszb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtciolwrjw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbforeuxa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtexcncydw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtmqgsebgb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtkaxfforl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtjaadvbps.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtpokfotig.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtmliuligx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtzqlngxym.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtybyysnxw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtzmukbatf.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtrabjynby.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtdveatbaq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtmeakwjbs.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gttreyjdam.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtdkvseukk.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtcethgzbo.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtyjfhyirx.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtggehvkvo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtfabubuhf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtbmwclhzz.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtskfmrhbf.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtkeawrfyb.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtdmsaudqy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtlohkppmf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtnhpoeeda.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtlrcdjees.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtusxxtgkd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtzxohgrwb.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtvkradkir.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtsgmiewvi.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtpihsqwpk.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtpjfqabgw.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtzgxalbsd.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtqkbjtveb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtvgmkfsgb.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtlwkbbpge.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtdpxzehzd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxrcbvlc.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtgauidvwb.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtaqqpdtur.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtdawgrvpp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtlzsrdxqg.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtrmlkhjqm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtowmslzgj.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtbhbiqgzv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtilchnskm.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtozuldboc.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtcvxlsqfh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtedbkhswp.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtebhsctik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gttizzoafb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtpuvgbert.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtwlumouxj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtxeodgfwu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcshgpmjd.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkadehrca.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtrqoiccfs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtpsjfqtou.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtaortvucs.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdlertdca.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtqeirvugj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtibufsgwf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtuvrjobwa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtrkzgajzl.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtteylfdkz.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtkgdhoiyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gtxrgwgkur.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtbfewdkfd.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtpzpqafva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtfnckhjbe.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtdfmaeyin.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtvspjrcmf.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gttvsetcvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtyvhrzxec.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtgcenffjz.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtqzqniapp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtspbeltnr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxuwawyxy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtohitdjcb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gthjtrjhoc.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtoatrxmfc.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtguatuydu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtfevrxwns.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtayvlpcqa.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtlbjmlkbg.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtcarnluve.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtdvulxhkl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gttebvnsyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtvdktkybr.html


<!-- 参考信息 -->