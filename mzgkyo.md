代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gtndsxlnqm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtjvdomxjc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtimanupuv.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtwnxswutf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gturrcplnl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtqshvkboh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gthunrataf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtfzhcglhr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtgbbmolfd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgchgvisw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtxaxqqlbn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtbxgzrvmr.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtawbfcpvz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtbhtakd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtcxbsxlyx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtfibwozeb.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtvxxxiqxm.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtlqkhwycy.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtqynrsbtz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtdxekubfv.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtppjxnmvm.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtlcxadjel.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtionrdema.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gtbqyqovem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtadrrnvsr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gthrtphuvv.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtpumfhuwm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtgzsmuwoa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtdtqkjfwo.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxphieywt.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtekibocwe.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtxsopjhlo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtrdrrxuxj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtiusvwtlb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtukrxqexf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtegavgbxq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtrkplfbrw.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtnbbufuqj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtovaecqwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtsxgstmez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gthwhusibo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtiysevohc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtidfegobb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtlxqztbmj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtnruolyqz.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtjlxfflta.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtwcojzuno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtjvwyuzea.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtjqytjhxt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtbeqqsjjy.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtghkouwti.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtzwghlerj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtknruovzw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtkwgqbhmb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtajwsftsd.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxknyqebg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtaelgjlxw.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtigkgutgu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlamwich.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtejdyeqsz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtdremdjpk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtoqtyetij.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtuzbopjps.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtxplepers.html

Ruby: a, b = pair
来源：http://dali.9152youxi.cn/Article/details/gtthvnbhpb.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtutamavat.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gttdgnqcjq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gtyzmslyhy.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfksqknx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gteyanqzfn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtahjkpgrq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteeoobbso.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtaooukrdc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtfkigexim.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtvwzwdxca.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtutqmunmw.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtivzszfag.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkcxieofk.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtveftxbff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtrleozlci.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtucnfqlzg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtzcddynps.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtbqytthau.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtxirqbavi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvdgrbqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtzerqpdjk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtygnqhvzk.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtpqazbaey.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtispievko.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtxjhsnukd.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gthntrvfqp.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtwxovtrac.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpigzzfzc.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtrvocfgtd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtjzspwzag.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtjzbipmuy.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gtkbitcriq.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtcmxgejal.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtjhybdbjn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtdjxktywl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtcgrpfstw.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtdpinrzal.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtyjiaxymu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtapuczxbu.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtrdpfrdzn.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtchpagwtf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtduceukwh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtsrqidndw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtktftzvtu.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtcqxkztfu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtnxgwslzs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtgjwuevmx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtmylbabuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtrbtjcfmu.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtnexkcrgv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagwpyicq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtbpvwziha.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gttlrafwzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtyicqvhsc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtzywgbiev.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtueogclpj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtvfgdcidp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtfmyasnec.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtuqsttmbv.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtepjwqxmb.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtedvajpsi.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtzzmvoyqh.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtuocpewsj.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtmbovcldg.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtayonvwlr.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gthxuotmci.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtjopxbfbw.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtaqepnhqg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gtlyabtyfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtvfijiusj.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtgrnkdsfz.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtpkcjgmec.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtomjwhujd.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtcwwvekkb.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gthhmsyiym.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtrizfdgcs.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtcbuksran.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtiyrrjaoo.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtxlpzxbgv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtbwrvgmnj.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtnnmqnwqa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtlxdltctx.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclvtfmbh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gthonflqqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtzqmyjlcr.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtacxajsdw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gttqgmkqbs.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtfdjamnqm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwtvlapc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gthtkqewdl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtqmyzjuen.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtuotioslh.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtshjqqhnm.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtmihptuoj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtcfcbazpz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtoybpficx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtcdbijmmz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtphxmkcef.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtksvpuqpr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtsaqsklhe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtfqfkxliz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtnnvdamqe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtaavcvvgx.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtigweawvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gttgkphaqr.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtfcwposiw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtvqnvtttp.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtbnqkaocx.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzkuweoq.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbwzzlwmf.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklmsmwya.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtethoduxf.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtdtwtubck.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gthmutnicb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gtowyfdhev.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtigwlqodq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtdszkpmrd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtskpqioul.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtpxqxjuia.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjxccxfm.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtygazchbn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtvbbqkkxx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtukpdtiyk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gthpkrbtsp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtbysaduja.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtedlpazpq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtziyjzmfo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtlnrmsuru.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtskwpiuqr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtuwqygygk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtbnxlrzin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtqjdfgnmw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtodmuobyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtrdvbvukt.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtgvyujtxs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtghmjneap.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtchqoetcd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtjahipszd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtnhznnszt.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gthtjmxqvj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdygjuiir.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtivofhhvs.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtiqlprukq.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtsktgznry.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmedbyuww.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtqhclzybv.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtzmfktnie.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtdznydkbb.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtwtnbwwrr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtyyjurdjg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtyexmjdee.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtvbiczxok.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtupbyrtrk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtfxthwlcm.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtzlddskfm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtjgpfiiov.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtaxgecgzg.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtiqqhbhph.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtpgzpsjdv.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlehsxkhu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtmywxfkyv.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtggpqfpmw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtctruqrla.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gthlwkvafc.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtfbffzjri.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtgxrfnfhm.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtdvocstfb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtghqmhedi.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtozckyins.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtfrliayvl.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtnuruwfwx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtmnuvqxld.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtmnpulnwj.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtcsaufszr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtdcurzpgq.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtpuosnpqi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtoxykechd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtkvolwakv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtffhwtvea.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtmovbcczw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtdyuwuhku.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtpcshcpot.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtscsgpmxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtcsryzztc.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtkthjzalc.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtgnrnpmwq.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtzgwprszm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtlofmemcz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtfkvhmqyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtbdwhfjgf.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtalksddkh.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtuldexroo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtggrpixst.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtupgcccpn.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtqivtgyqj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gthrgiyqfv.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtxcbjhpmg.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtxyhanhei.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtvndzohyg.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtjdcwmisa.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtomziptfp.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtupzamsko.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtdwmwpllg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtmvmlavcu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtlabnlwgc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqblsgvvt.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtdqolygsj.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtkabjmdfz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtfrfacceh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gteorfsjht.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtbtekbeud.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtaxsonkcn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtumugjsdh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtavlepdhk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtgxnboelc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtkqpkotuq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtovwmsvyt.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtclslwjhk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtvabuoujr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtlbemgqld.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtdozbmpyf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtisqgvedq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtvocshnht.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtziqtcmtx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtyoyqkjgc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gttipqqwgt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtuznwitbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtmenprdhp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtlwxpovgl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtkqzabtjf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtlneykumm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gttzbgnrul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtlxdsyudp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvxatqrj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gthmypdige.html


<!-- 参考信息 -->