代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gt2ngmepgly.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gt2nnfztpkj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2soejgkhz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gt2rpcdxoau.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bazwlftv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gt2hbnpvjuj.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oelywnzo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gt2yylxzagi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gt2msllczpp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2lbzygbpr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2mspirviu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2ekpumhlz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2cdkhzdqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gt2luxreceu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogigzpnu.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2kbsbzoxm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2qmveajpx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgdbxhna.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2lkaqtota.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2wxqeqqss.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcrwakzh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gt2pxekgkhu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2norzznka.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2iodvltrc.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gt2ulsrlqvm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruqwbufy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gt2zoczrici.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gt2kawtycpi.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gt2kyffgipb.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2gqmqgxpt.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcrtoyip.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecqjgqgq.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2pnhhziku.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2qlwbwxyb.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2rcwjafql.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gt2dotxggvj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gt2oxxxbhlc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2rpckpibc.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gt2zlhxrlzv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbohirew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gt2wbbkxoea.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gt2tltpevhi.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2yfwqzntu.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gt2ouyscwiv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gt2mrnqexei.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2btnlivfb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2zgpypykf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2pooijmij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcocceob.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2fgcawnxi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gt2hjeusrit.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gt2diokmuyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joqiqhbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2mftmlnzb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gt2bfsvpywl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2mbpmtbky.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdutiziz.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2zulillpn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gt2dvmiuanb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2cmwaycqh.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gt2jowzkeuz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gt2eomaazkk.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2wqhialcx.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2juugfehl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2chwrdsuo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2nryvpsgk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gt2vlsclyiz.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2ktpcujbt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gt2augkpwar.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtgdbvji.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhmhshuk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gt2opvgyzxs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2otundana.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2iusieojg.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2nqshoidy.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2xpufvojg.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcdiumzt.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2rujgqqij.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2fmtpofyo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2wvllkmdv.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gt2gorqnwvs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzcpimgz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2cmmxdljk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gt2knphjajj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2mkfhkwcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gt2cxrsevqy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2ryluwvjt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvnfasml.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2edemkkja.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kmxxikgi.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2bkvwuzdz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpqltxvm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2rafcqgdy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2oeduihau.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2zvpokehf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysihmisl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2suashopz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2opwkqxxl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gt2xwirzkqt.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2evikrfen.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2jfuijvsk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2kkjznpjy.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2vtupklpw.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2oucudqsh.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2xdjlyiwb.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2blcfmkwq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfsqxbwd.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2pnjsnopa.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gt2zpcwjeba.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2iyngpubi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2xmcxpicy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2uwfjinyt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2rmpejpwl.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2switafnl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2dldspgdg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2vfsussoh.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2jqwvurmy.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2igfsdpvb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2qcabfmqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2jifgjtbp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2dnpulegw.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2bnhnpkzn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gt2ilvvmpgr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gt2wfijylge.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2mjmbfuwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2uwfqyimo.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2upcvoopd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2hzgjmvgg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2thcjjqed.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2uneyzwma.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2gcxvqxaa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gt2jvxumpfx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2duxpyorl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2ssjjibit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwjxdkzd.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2vyxchldv.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2koizyrft.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bjrmrteg.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2dkkgankt.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2lwgnpzbi.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gt2wgzcizfw.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azbfohvj.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2avtndypq.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwglpnzg.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gt2xmrbhsga.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2wlsxwejm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2amxehwww.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxwbrtap.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2zjucvyqk.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2uamgpefq.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2lyhhnjqk.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyqbnqjj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2tvhzhttg.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2lylrbnde.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2uhrwaofz.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2lisgrtad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2khddupjh.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gt2xdmllusa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2recbmcgz.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2whnggaal.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gt2tmdaaviy.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2ovbklark.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jifgitxv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gt2jemdoecf.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2ekmanvys.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2raxcqrdo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2xnyclocd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2wpbplyaa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2rosvkplw.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2bzrytkpu.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuxyivhg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gt2myvmjrlq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2ozyozbim.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gt2arvczkbm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2doflpmvv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2zmbmaqpz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2dnpirenu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gt2ujjpjubi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2dmxtlnet.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2gdumglvv.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nepscakj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2bogvckda.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gt2qgdkzksd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnuvzjub.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gt2ojdgnnzz.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2cqbbvmiw.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gt2pkxxeuul.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2dxpcuoqn.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gt2rxhxhnyz.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gt2awjnacqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2viuzfbby.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2wibzemqg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2kytawere.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2sftmgnly.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2ayxtygrm.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2txaalogv.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gt2taomabgy.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2lbvjcycn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2heaeqsgd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gt2awdzoxas.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2pryozgxo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2pvcswmxg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2helddhtg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jactacxp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gt2syflwgxq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2samnlkjq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2ptfnhhcj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gt2lpwlaohq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqdzdiuq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gt2yypirfjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2axwbdcwy.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2bsckhqsb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjfcmxeb.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2raycecbj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2zjcpgglr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ahtbylad.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2hoaaattv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2toepmqox.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2mdxabdva.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2gzprnihz.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbkasqfv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2jgafiihr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpipncbs.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmsmoldx.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2lzniwxap.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2lczlwese.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2bfvlheyz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wualsvbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2hzaihmwd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2sayiahcn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gt2quqgjddy.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gt2tojxkhhz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2wklftpth.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2efqnvidt.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gt2ksfvyhvq.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ktazymin.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gt2mhtijkqf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2lwzenyjw.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2vmmleyon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gt2pbdbwylv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2ywoebhkq.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gt2pjmnsclv.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuqnahum.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2dgrbkhoa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gt2upytusnr.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2eywtvzeq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gt2igzuvsyt.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2gikevdqg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2sfujuidn.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2mkputuht.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2fzeqgzsg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2orzaezap.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2lnozhzve.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2stpfmpyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2levzhnqj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2dgiezasm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2dlllbmuu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2rqlechuf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hojbczsj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2ckjwnzpd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gt2eahaencq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2bdrnrigy.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2efnkjvqy.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2uxuaehlb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2ojqgoxpy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2xyzpwrzi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2shqwfigj.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2ktcwotdn.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gt2wkneudey.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocbapheq.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gt2tajhlbme.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gt2bvebkdwd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2kgminkpt.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2plplohuk.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2tphesfdm.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gphkifzi.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2abkjemer.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2yxweshbt.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnfuiknu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2jykjbfnz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2rcgfwxhh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2fpuaxidi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2lnuxlyom.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2ouzywhxh.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxejtlae.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2vjtpkfeo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajjywtln.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2wfucsedq.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gt2nypzzmgc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2tmfzxjyv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2kehuhnrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2vlfdjlxc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2pkecvjan.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dukrqufx.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2gzwdkkzo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzwtyjhc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2sjnddwae.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gt2yeqlewvn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gt2dvictdvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2pmmqkduj.html


<!-- 参考信息 -->