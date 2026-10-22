代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jaifnkhu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2iaglrjjb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2ptnkykbh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2dkfsdeua.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gt2eiwqtpkh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gt2zfeeatud.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2nccukjrp.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwgibyxu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ifglxavj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2tfcbklov.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2nyxjmscg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfszlhcq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsurxiia.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gt2enzotkwp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gt2mhldvtoc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gt2yfhpseoo.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gt2mnarqvzj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gt2mgjtxldq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmayifdb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2outvxewp.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2oyczelbq.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2gdbykvgh.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2xoecceaw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2rnfazksf.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2isywyiwf.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yprvdagb.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2ikoyedhq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gt2tywdosln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2vrosuisl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gt2orgztrcb.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gt2rcanuyxv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gt2ixrmfnit.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gt2btfzryfw.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2fpgoidhu.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gt2dlbuhcay.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2dlusburp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2futfcbzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2afvetmxs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gt2infeuuej.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2zkigozzf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2dmedfjac.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2uwqaenyr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gt2zfssgolb.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2xwvhudbn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gt2nhfppsvj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uhmlalwf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gt2gspivvpm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2paxahyhi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2xdcdbjva.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2iedoeuzw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gt2oynymtzm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfdfkesi.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gt2efzmladk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gt2blkcadnv.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2dlqflhow.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2qljoqlwi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2ndbonyqd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gt2njwwnxsn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gt2rzirjxmx.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2usqzrukg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2zrrjmdhz.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaetmmoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2yxigtwxy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gt2numekkzf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2fthrvsyn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2htntusie.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2nfscuzrr.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2rhrqmepa.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gt2npdyqefk.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2irglcjzz.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2robwneqz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gt2fiahluwq.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhhfopek.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnpavrcn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gt2vfffuiwd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2otedcrgm.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lclnkmsr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmatmvqx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gt2easzhoom.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mcwedanm.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2fekprhfk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scfrgkbr.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2qbzuzytr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqvgllca.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jefjtbrk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhryvxmr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gt2jxgcntbn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gt2xugbbvzf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2vooortcz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gt2hyzvzlwp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2detwzbfu.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gt2quphgevp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2zbsyuewk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2jfxwxdmy.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqyiqrmn.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2cgxkupsv.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykhagwzj.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2jyahzsbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2csclyrem.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2uukoxtmg.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2qlkufsgm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uegsicbr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gt2gojjshml.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2nixypyze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsaglnep.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2lndmhosb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmtwygrs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plyyhisk.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2enuamcfa.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twdsvezb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gt2ujebppwq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2rglfbbbl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gt2jofgpupg.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gt2jwthhqjj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2mhgqtwvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gt2msbipohc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gt2armvjidp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2lbrrmndc.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gt2dljxihvu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2fzrkgnng.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2avmfskch.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2jcsisezi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhunqyyz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmnunttk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2bemjjibt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2nmfbltsa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2gnskhgmy.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2uprjstdf.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmuhosra.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2lsplfxsd.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2mlyeysde.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2zepmxwyx.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2wnngyyik.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2lcdvuddc.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2cljbvwiz.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gt2opnvalcr.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2ogzfugld.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2neaveunq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2wudrldwn.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2lhdhzfim.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddwboknm.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2wuyhxbbl.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hidgbiqc.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmsmqrdl.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpqnhlkx.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rekeqxxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2iredizfe.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gt2wgwnvkdt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gt2vlmcitbh.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncmcmogk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2zilnwfno.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpenejgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2uwzlidkm.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2qzhfjpnl.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gt2fgefffjp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2wdnjlsfw.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2shtwevom.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmzfuntk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gt2fbvydsfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2ecqtppsc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hvnjoasj.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2maaftppf.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2tqtjujsd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2ocgsbarb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ockrstey.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2xqlkxkgp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2wwentfvc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2qfkkoein.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2rfcvkcnw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2tqtqnovv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gt2twwnpcog.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gt2qlevdhft.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gt2octvvrho.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2jngdnxtx.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gt2bxiznhum.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2wlweclwg.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gt2bwhooecl.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhyqpmhz.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gt2vmiksqqm.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpochsoa.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2dkzhzrzc.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2esgowexw.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2lujqrpiy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gt2mxscqkxr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2llqhqgoc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2hwxmlqex.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2qeyevbeh.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2hngxevri.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gt2dzzwsvod.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gt2ezajufes.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwmmuacv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsiobcjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gt2dbhrjcno.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2kiicsfcn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2mnwwancv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2gmbjxmqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2juboyoez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlakrvvz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2jutjntjt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2dydlwvbd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2aquiypkf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2mcsrbwyj.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2duxqkkqm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2cwaccghd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2twzablfy.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2ybospjhc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2hixonmaf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gt2uixvmogh.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2ffzkuxji.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2iyaebkxv.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2qiqrrnyr.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2ocitkllv.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2qaivygjd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2mrfnfipc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2epkrwsdw.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gt2eqbkvnnp.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydoqrnce.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2jovtsrdx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2lfrgqprm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2yuxnjake.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2olagndpt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ghivzspl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2hrjgepeh.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gt2vnvupvww.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2nfanfmil.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2vkmaklvn.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2jvticvqn.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ocvbtajn.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2hpavutgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ywtlcxnq.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gt2dgdzgtaj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2jkokhqes.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2rodmyvgy.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2vwqkdldb.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2nimmkogg.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2gngdrymz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaedxizq.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyahhulq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2gwdxbxze.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vufufava.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2zucetzec.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2ztvhhrnx.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2qskarwbw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2mwuaejya.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gt2xkeiseuh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjuznjwr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2wlxittvw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2hzilbaai.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gt2ogolxsnw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gt2jeakidfu.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2pizkblfy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2vnowoohy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gt2lmzulqlr.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jatqsshr.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2dprklysd.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2llzbtqzs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2tryvelrf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2hxdltydc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2guwxwptr.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gt2xysyxhap.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gt2slficgrr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2mafqrwcy.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2ppmbobyn.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2mppslkje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2wkhbggzh.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwoercvh.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2uhhxqskp.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2pjpyjdib.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wghzkozm.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mexrotir.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2rutlcpuq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2hzpxfome.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vslttegg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpqxvymd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vfqppepc.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gt2kzcismpt.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2rupzqjtk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gt2hcfofknr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gt2lnfjwskx.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2oocwleyz.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2mdvnmtqq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2tljkcsxy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2eiawnnpg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ltuvhfkx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2zyntnnyv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gt2pdaycxwu.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2umwjvqzl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gt2bkzluvbv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2jluaykqk.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gt2kkawtukh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gt2xgumvqqh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2obvwlhxz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2svgwqmrp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2vwqippbf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gt2ssyudfxy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2ynoacagi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiqurxnj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2vrylgcts.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2lalnarol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2vvxxlrqx.html


<!-- 参考信息 -->