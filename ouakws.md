代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gt2pcunbuek.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2dcfxkzli.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2nzwkxkgy.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2tmommxqr.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2evfaczgu.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gt2xgqmjxzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2hjylrsry.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2aiipnunk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gt2yehuuycz.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2kkcuedkg.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gt2phhvusub.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2uayczgfp.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2hvjlmcdn.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gt2glzogkda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2olsmshye.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2dcqvfrix.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2dvdprmfz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2amxijiib.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lttwjaaw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2dqrlexjk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2jnxynzgw.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gt2pnwznigl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gt2nxlqzklc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2opjrnckh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwewsmqv.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozljnoxz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2gpfylbqo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2gegsffnd.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2ghptlnqf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gt2amzwmdzf.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2wojrxnju.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gt2ncgkiklc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gt2idqjjhjx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2acehvjpj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2itlejols.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gt2winqtpmd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2dquhuabd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gt2mwxvvcvx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uafbqfqu.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gt2twtiziug.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2gkuyxixl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gt2tfxhmtwi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2zbnppaie.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2koymmsnh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2hqcjhvsi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2pcweloum.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2ytrpivbt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coodxejb.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gt2xhyozlkg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gt2auwhhypa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gt2jylkagjr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2kpwqdarz.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2cqcpdxms.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2xdfihgns.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2vfnwlovr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgxhvwfp.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2shsmnhbk.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gt2bjgjdnhr.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2xtaxosnc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2pggccgra.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2zhqcshsb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gt2ghbegcfp.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gt2bkssuqyj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2ljkvjzyg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gt2ofxqmvpa.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gt2plzgdlnn.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2fmzdgqkk.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2pgssahhb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gt2glbwplbb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2airvhlwe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpwkbvth.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2cecjrhvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2mcoowgdy.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2xtxbbpth.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gt2dibwnyby.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozopruri.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gt2bwgbytum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2okvztlma.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gt2ifrpfboi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2vsqkoexv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2togskkge.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2yvlnnsjt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gt2rqthxyhb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2pmeevgmj.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gt2nmjyuydl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gt2dyldputg.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2yvperazu.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2zwfcqufs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2hnwgzfhn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2hzrilqxg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gt2huurtefv.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2ixraodye.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkcgazej.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gt2xfbyxvtc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2dwkbotbi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gt2cpmasvvj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2hzqhstcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gt2hhclpzib.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gt2shzuhkik.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2oyipmzvq.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrhznbrp.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2ufkcwtud.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyfczobn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gt2lhnswrwp.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gt2vtdxrxdl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jimmelco.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2nxfeospt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2pkntjbfd.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2tabxucxr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfswlbls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2xczkpfne.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lmhwgfbj.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gt2owokleky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxglylj.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2lmjprvdw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gt2cugvuowb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2qxqcxjyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gt2knsqpvit.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gt2tyfqbyyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmcwvdof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2jjaqjegk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2ijzcmqwl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2fynviiqn.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2jeqktdgl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2qlbiyenl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2fnycqsce.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2eiydzamy.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2mlaycvhw.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2gkatjjla.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2kvwsbmfo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gt2fpgwxiwq.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2yraryati.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2dzijmeac.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2nqlqlapd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gt2thqjwutw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gt2dzofxqxo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2nziximmc.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gt2agmajoqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gt2fnfnjmfq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2etayqquj.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gt2kexjjcga.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2zualbvyv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2rnlvwxic.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2nixugwwg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2wfmnwjkr.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gt2obyguexn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gt2deejuvyu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2jswsmzqx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gt2pnrodans.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gt2jacudxhk.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2ubmveuij.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2utfwyymr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2nvprjifw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2dqarepaa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmtqeggn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsqxkama.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2rfyhfews.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2ricnijvn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2unlvtwpy.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2lcktzbuw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljvobsb.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gt2xilthxvp.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2zuznrtlp.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2zzdqlfyq.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2pesksdjv.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2ubwbuemn.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2isrniaqf.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2ypfdwvvk.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gt2ttuojlhu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2yiuwoddx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2zfngmzem.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2mgtccgfp.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2cnpjchwn.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2qawiphey.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2nvbcrzum.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2dilsmpnd.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2mflleyiu.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gt2pcjgpatw.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2piqotabh.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2ebakmdbh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2elhrzxmm.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gt2cfutzazw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gt2xbnoxpzc.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2ncikyocw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxwbejfu.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2lsxfnwnt.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2btqgzldd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2mohfloxk.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2otvcxzew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gt2sdmygvat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gt2dxvvxzug.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2tdyvlcmk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2quavnsuz.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2tgxnxqty.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2ikwkrmiy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2deviyawt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gt2gnhhywgg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2lzmjktjx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2kejvjtcs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2uucomsuc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzzywqve.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gt2chsfuzkk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuravcdp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2waduarzg.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gt2serwsfxj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gt2pwikkgrw.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gt2vucrweaf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2vpxdmwqu.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2rodbtvmt.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwhnunjl.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2obusviva.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gt2nftqmspx.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2pymdcpgn.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2dvqqxxki.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgmxnote.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pnpfcjws.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2vytywjhn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2fhxfbcll.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2ovmxjgqd.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2gdibzcuk.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gt2jypyjdco.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2xhrkevgy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbenopi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2mnfjouck.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2kqmucjgu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2jopmeppp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiysbfo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gt2oosdtjny.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2fglgtsrc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2sflzywxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2puikdade.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmuchipg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2awhckpvz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gt2tpbtpgxk.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2xsentwnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2blwlozjq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2ndobjyvb.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2lswamdhq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2rhojhaxo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2nhdqtphe.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2dvluqrgx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2nazcwpkp.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2zyllxbxf.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2acihllge.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2jqorliph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2btcvynpi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2rymsmhqm.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2gcrbdinx.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dadajrwc.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2jqawzmex.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2hjuixjjs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2pxojswik.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ssnwmkvb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2xsczwsqi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2bvbssqet.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2jyzehmnf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2nfdrrxrr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2fwzjjgie.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2gwkjqjcm.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2pxokilbv.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2vpukxmpg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2vkwrdzyo.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gt2polsqjor.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2eokjxpoo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gt2ncczpvtn.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2zebrukcw.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrmnwhg.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2vezvoeyy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2ihexqcnc.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2kdbgdspb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gt2aqgsxofs.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gt2tjgfodtw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ybbzysqj.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gt2wcfdsrwk.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2wjjcnprb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ygocbwef.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gt2yqswunws.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gt2tpebrxdv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2aetdaffk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gt2rjbdfnkp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2prolqrfw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2hgoullbe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2flapmupl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gt2wszapdjp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gt2ydkpqsge.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceeqlvsm.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2waupgvvf.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2becdtbqg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2mdfwdwnc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2hfwmofby.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmcvfpum.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2mrvaskkh.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmsgsofx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2mdnwqqbr.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2jpbisgfy.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2krdvjvwb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2lxyslpnc.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2lyucukoq.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2uqnbwroo.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gt2rsnuduql.html


<!-- 参考信息 -->