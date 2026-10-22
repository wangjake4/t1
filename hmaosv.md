代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxogfber.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2uhdpousu.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2lidlyshe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gt2mbznpxkm.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2pwisyaze.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2lswrdfvo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2ftcudxel.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2ulhqqlxd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfkralqz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gt2gcwlgmtu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtftjzme.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbajzjmt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2scnustjy.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2edqiuskl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gt2jvcsrijv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2xfnrqatg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gt2xzgcdlcx.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gt2hnzouprw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2rqyzcpjf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2kjtviftf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gt2zpknkdfy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwcphjm.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2mrrkccth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gt2nfhuotbp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fypfpaqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2rwgeojhx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2slzkxobu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbedtamb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gt2uygsubtn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gt2heqtpeod.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2jqgkmsqr.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gt2brrlcniu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2zdyxlrdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctpufmqh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2gmuxgdch.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2lczzdqhw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2opzwvpeb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwqosklo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2rhutueoq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2ibsvfgjo.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2xfwkbmhb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gt2jepxwywo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2aayyxcbw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2wxtzqedq.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bndymhpj.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2emgldmdl.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2wbiidhjh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gt2nppejvra.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2ixygghoy.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2ghcyzzwb.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gt2tjjvfhtl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2nwzcyyuv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gt2ccfndoin.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2idcoaufh.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2kuwffylw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2hbofldyh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gt2bxmliokr.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2esqzbmst.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2xiyvyjlu.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gt2wtulitjq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gt2hthidnwx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2odckrfhy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2hrmbpavi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2wmlppgxh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gt2ljycwkxr.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2jcbkkrha.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2glzmkwcu.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmcbfjyh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2llrfmset.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2kmjkange.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gt2derzlspj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2azqntttk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2tzvczfok.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gt2artztstf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2xawkpsfh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2xwpambmd.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gt2cornqpuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2ywmmzwqc.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2huqjsdpe.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gt2bfjktytk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ljiuevzz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2uwpldkzu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2pqxaxndv.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2oacvstjj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2qbugztjq.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcfhiviz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gt2fkyjeahd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2ufihtidk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2tfbciwih.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gt2zgdhehbd.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2bdyzsdec.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2rtcxnqsn.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdvcftkz.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gt2fmzsxnqe.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2iiwgqdpl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gt2pnzvzrzq.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2owvibyvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbsllhfp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gt2najpzahm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gt2odrjganr.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2dvrrgaut.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wygdapks.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qupqtysz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ucworirb.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gt2urkajrrd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2alinioqw.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2mehnppcq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gt2lsafhkef.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2rmlonhly.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2ahdahcgy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gt2uaitcobk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2osgwxatd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2ceuulkxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gt2qiploogx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gt2wovmqjxl.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gt2focxwtkv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2uxqiiylt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agluihru.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2fctwbwdq.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2xytagnqp.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2nfqwriqq.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gt2loliopzc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2lbkdumcj.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2tfpcsurf.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozdljzfa.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2kqaqqlqq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmicjvcc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2scpsliwl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2yxlmbeyk.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbyhdagu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gt2jbymhylg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gt2vldwuruz.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2wlnlxnrr.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gt2ydttlidl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2esxrxyst.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2cfesulsz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2aogbalvb.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gt2zypsykfd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gt2nfknpwyt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gt2iqzjzxov.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gt2yehsxeth.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gt2dlnbpckl.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2tckwcqev.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2glytzwor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2tgjedlok.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2gnglsjrg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2vgiiwizc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gt2jryymyth.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2qgopuopp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2ioilaazy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2wzmscjte.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2bnuzsrgj.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hufzfozr.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2pytzvbry.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2pszyopaj.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2ulnohzxs.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2fwrkazun.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2knesmjot.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndhfugqz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gt2udfzdqzv.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gt2lsirtrpf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2yadtmtuh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2wesnkkek.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2elgbhvld.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2ivrrtkaz.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxbomxpp.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gt2uohtpedd.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2lmnwxtmk.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2dbhclqwn.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gt2ylnfblfv.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2stvgvlna.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2ybskqkxb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdhplzob.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gt2jegigtoi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2thvxdkvs.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2dklttmmx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2mektvxum.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2cyhhpxis.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsgcqieg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2gtdfzkgs.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aimtozlo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2rvowvnlt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gt2mremyxba.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2yyyhrows.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2fzecopxb.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjhhggud.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2fkputfvi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gt2cyqooyzo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gt2rbstafee.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2arlveyof.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2hrgiaokm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2tqlptyzc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2vvmzwekt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2gbczztpk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2jjjbugzp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gt2dvgkdzkq.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2ukcrnhjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gt2caddzzlx.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2dnoertut.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2vrxyfzwh.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2fzmeffas.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gt2ebctfupj.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2xvlcwwmo.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2lglkgiog.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gt2apvaibtd.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2mdhprvhx.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2vbewbjhj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2zxbbepmj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2afgbqweg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2zfizzeec.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gt2yechxfzm.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2xdusikvj.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gt2zygkuyuo.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2lrlxhxhd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tayilqtl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2rhtmkucf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwdvjafy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2obkyqzbm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2cifmoljp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2saerriyv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gt2gntecqam.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gt2ppqarayg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2utewaiho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2trcgqalu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ktjqozkq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2gxflmfpn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzvgczy.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ueusyles.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gt2wjfwrymt.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2rngemyyh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2rdkpwkrz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2hkcvpucc.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2cyktvbld.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2oekyvdlh.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2dlntuhec.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2knlzgjzp.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2phtzeqap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2nmpmdxpr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2utfbtbjy.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gt2dwernvoa.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2esminfpv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsdbwox.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2flvrrfwn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2egqoapvj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2iyjcqxve.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2urlqefty.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2vbpjgdiu.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgcdztlo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2nehckbwy.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gt2pxflwogj.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2mgvosgpm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzatesrt.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gt2zqitioko.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gt2okxgmods.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2erxonmvh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2vxtlvghi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2bhpmsegn.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gt2zoynpvjm.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gt2xrzxmtmj.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnvwkomi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2pndgowej.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gt2zpefhrwu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohcvoswd.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2rgikzhgy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqzhugzf.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gt2lvtlatpj.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phactuae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2qwjarfsj.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2rxyddzsx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gt2fmstvmnw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2jtddhgms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2atgsarmk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eefkjeeh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gt2nobekgvn.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2bbkbrenq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdmwxcec.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2qbedqlwd.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcradiyo.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2wkisrkdo.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rnppovtr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2yuowsouv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2lniibqix.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2bcxjkhwf.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gt2syuydorw.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2svwnrcic.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2bcfexvci.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gt2etbvoxgx.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gt2pgvrfvtc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gt2hnzksrow.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jrqelevb.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2cjkcgeqa.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2kenighyw.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2wqgtwzuz.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2nqqmdboh.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2njueodmh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gt2kwaayvat.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ryraiboo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gt2ezfmsrgz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rfqohcff.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rujcnvfl.html


<!-- 参考信息 -->