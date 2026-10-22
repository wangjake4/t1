代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2vydjzoux.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxjnmycu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2hdlzytnu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2asxksbct.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2mmhsarkf.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2ctghgoln.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gt2bmnyiwzr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2dhdonxjo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gt2cftzteab.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gt2xeeszerd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gt2wxbfecaf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlaeozoi.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gt2sqmeuuzp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gt2yqkjazyj.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gt2xetylgmq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gt2tstxkwqy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gt2yevvnlet.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2nlhndzyn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrarjxgi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gt2bieijjfu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gt2aprjarkv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlswoubk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2eivepexe.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gt2qeimakyk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2sgvhwhng.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2tpssllis.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2iculkrgj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2iqrprlmb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2rhobdvfh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gt2ukfxnplq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2tvlxopjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htlwjvou.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gt2gjtdmveq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlektclk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2nncyydsm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2ikblmwfj.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2pnamutkm.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2txajgcxv.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gt2uoqkmwez.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gt2moeghswr.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2purzgrvs.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2xemqqzvm.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqrksxng.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gt2acgawxfi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2poclxmqe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gt2jmxdcfhy.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gt2fjbyqaxg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gt2mgxuvimk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gt2pmuuvgsh.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gt2bbiefysz.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gt2zdpbfctu.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gt2ncspqwag.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkxlauti.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2jjlklqqo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2mqikavis.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etllvbcu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2vooveybj.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gt2ybbvloze.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2qkzotfzv.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2moljgltp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2jmzwvfkz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2sktqbaza.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gt2bduwfgjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owzwqiug.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ojorfpek.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2muoxwaqc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gt2etwugosk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gt2teyzxhnu.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2amgggvac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gt2rurznbll.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2gjnjsxrb.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2ebxnpfpo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gt2rrgibsmq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2wlucxaor.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gt2ifuhnlij.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2echpfegs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gt2vwfynlkn.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gt2ygeobhql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gt2wlzbylrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gt2vlxlxjfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2bamhdmdr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2lffbiewj.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2tvikejoe.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvcuzjrd.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gt2drlldztp.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gt2edobpbaj.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2ryoxmscv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2oppfynuu.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2htnhtxga.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2roahqwrr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gt2gfjdjbhq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gt2ponxnofm.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gt2dihpyuss.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gt2qhorsriq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfyayqsq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2mgadkpom.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gt2sdxemkca.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2djyfxugn.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2dglgjorp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiolxtdd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylpgelro.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gt2tkojfszz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckxcsaee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2mpcjxywc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjvgjdjc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2fhtsbxzh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2xrmpbuiy.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2xdsbpkur.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gt2nuqsjvou.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikylngsd.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2wpdpimrj.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2mqdtfwol.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2jaupdusg.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2yjmhmdhc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gt2epxmuntc.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gt2iwrdexcy.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gt2tvszhcbg.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2hdgzydkg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2slkgmcou.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gt2ohjekary.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2knpysvai.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmweyylh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2brguxqth.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkxduulw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2smhbqrwy.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2iaetrvum.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2wxdoxsdj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2poeqobbd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2tvszkqgc.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2kyhxegha.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2xyfbajnq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2kergjtxo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gt2enwapfge.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gt2staekooo.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2zyusboty.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2fdqrqppz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2jqgiuqqe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2gdhpcotj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2fleohxwu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gt2ygbwpnnw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2lwvktcvf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2bwgadhem.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2yghqchjw.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbzmyhzu.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2iaooffjk.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2coyzgclw.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2pkmjpvfl.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2ovyewaqf.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gt2cdjxezsn.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2porykqve.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2aiqbwpay.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gt2qtzinsca.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2ayullxzr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygerlmib.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2nnwaxbqh.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cenotuzo.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2nrosietv.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2vqnnblfl.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2qyqtaffg.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gt2lkacpkjg.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2rycnxjbs.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2muemqroo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2zaqqzuka.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gt2xxkdslix.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2yvmtirvw.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gt2feezlfny.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2bwbdlwsn.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2sidqyuyw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2znlpuggl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bssjzsjp.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gt2oyloipup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2ovgmlbzk.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gt2liwiyvfx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2ccvlbiil.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paduaysm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyzdkpnj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vydkwdda.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2argcjpal.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2uorsyruh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dntntltb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gt2nihwmzxz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2uosbsknm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2memjxjmi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2kbokyaee.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sonsqaxo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcsqoqut.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gt2pmuycmdb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2zcqoifxx.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gt2hadxtvko.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vorcnpdq.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2ddwiowma.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gt2csxwbxys.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2drvrcapi.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2weucxzpn.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2gilkljzv.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhtzxbli.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsdxelcp.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gt2xgjgqmnt.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2bvxkgthb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2enhhuiqv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2waflltyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2jibklfyv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gt2wjzruhjo.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2umdmpjkt.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gt2ndsurqfd.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2otcxmmxk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2jjsklxjd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gt2tsueakxh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2kilsfxza.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fouyeqwr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2tayzntml.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2dwkdufda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugilxdwn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gt2xyerrwlt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2sayrpxdv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlgzavve.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gt2mpvqehrj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkxmfbce.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2akmspkwt.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2sluhmhpl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2nztvrrwg.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpnenvrx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2iqpsupgv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2pghadozs.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2czxueewk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2kodinovx.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2bepkfytq.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2ujnbmibw.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2nwpxcnrb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2gwvzeplw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2eezvlfbm.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gt2ycngnqug.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2llmdzyls.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcgfxzki.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovrqimjv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2nztkkwao.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2lzqvopex.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2tmauknwj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2qxqzkqbj.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gt2czpaiard.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2qeqdqlfu.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gt2hzdipfhv.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2phhclmen.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2zbpbhblo.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gt2uvzjyvhz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gt2cdraxifj.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2suhqcsgk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlchwxtu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2bqvrbukc.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2indqqpnz.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2gzwuhtdh.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2jwmvduww.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqvyddfv.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gt2davjfzaf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2rrpmlmuq.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2clagiybu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2nkkgsxkr.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2yrzqvdcl.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gt2ubggavzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2jrcoukep.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gt2fixphssa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2njiyeaxl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oadznrou.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2gfyxflvt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2ermwvuez.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2hkiurhcw.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2cnkgtzmg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2pqxrjpfs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2flfmaqni.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2mzqewqux.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2ztrokwln.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ajcdeqsn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2nfsxcffj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2wnpdvpjw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiqhylao.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2jutatwbn.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2kzattdar.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gt2pwohmrma.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gt2citbzkii.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omsadpgp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gt2fonupfks.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrordiyx.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2nlcmnfrf.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gt2ugjjbont.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2kizhndln.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2mzrztwav.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2lknvuvwb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2trbvcrxb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2izokhfbb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gt2zfekuhyv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gt2rauklrog.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thkmzymu.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2qnbwdweu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2rxbgxlwx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2brwzenpg.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2qngaxgux.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gt2dymwuohp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2uyfxumdi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ehlpslhb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2mcqvjlye.html


<!-- 参考信息 -->