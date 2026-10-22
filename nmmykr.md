代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2uztqizdl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gt2zanlglxt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2ndalgmla.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2wiywywak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2oxttotbl.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2bjeqkpii.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gt2kfxyztym.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2vyvanozj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgfdbqnf.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2sausqwmy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ykkyiejx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2cpwymjer.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gt2dhklqjgc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2ihphmthx.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gt2cauniilg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2lypkzrqj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2qoxxpyoz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrxjhev.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjsxmvel.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gt2wqieihok.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2vecicamw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2fccjcthz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rjduqbkp.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cryrzlco.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2xzygdnli.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uefktjif.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2drpjxcpw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2akebfmem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2plyoxhgs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrfdacdv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2gmhchhro.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gt2obldzitt.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2didslvrh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lekilcdb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jednlyta.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2whfldugw.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2atixzsmt.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2ubgnlhbe.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2rvgdbxbj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdrpwkcn.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2cmlxbbte.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2jzzoawuk.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2mgitopxh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gt2ykddngpm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxdbisiu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gt2iykximmg.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2srdcewlf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gt2sgqigjcy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvkeriur.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2ocsalvcf.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsraxasy.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gt2gipgrysu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2sjrdtimu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2rraquexh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2dokcrujb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2zlojjgmk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gt2rzhxsynq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gt2czhhndcu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gt2fwyzduir.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2uuymlinz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gt2qwbzbnxa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2zvkspnsd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gt2jtjbcicd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2euqhepri.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcganbjw.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2icabsezc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gt2jdunvuim.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2nisrycyr.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2idzeqerk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmtmqejc.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2puykrfbk.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2pctvttba.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gt2oqbmdqhp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2jsrwqncp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mciibczj.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2vvblmsas.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gt2bmdauzpy.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2atwrcrxk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2rriytiqp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2tftmyvrd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ojrhngee.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2rtvatyfe.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2pgbefpxs.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2llvscxcn.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gt2gmsvtlii.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gt2okafubvm.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2utyyuahp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2azkvhpce.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2txejyvhz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gt2hqbsnygg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2jmovglwv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2xbkhhmlj.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2qmcdjgbi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2adyagaua.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2jtfwjtzi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cfnvaqkh.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gt2adzpcnus.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ergnsgah.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhximgev.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2oervrczw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2snawyres.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2sxdvzzfc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2pxhiuntj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrhsxzir.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gt2fcdgyjpx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2bxhjrtjs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2evsfoiyi.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gt2ogyaywjx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2fptosyvu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtlhjmyk.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2dsbydcro.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2gwlwamaa.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2kuybvtwk.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gt2brogauxf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gt2mhkcgsfg.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttlmcudx.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2pvkylxfr.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2vwfnktid.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gt2uenkutns.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxhblwwl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2jvokiqij.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2jhoauwlh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2ktaktzbz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqzldhja.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2erwqfhai.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gt2bdiwiqcw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gt2tzkauvpg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2ksoelwjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2bfwgmmlo.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gt2kbysrzkg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gt2khjzxxmh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2vtrohggn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2bakgblui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2nhwldyss.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gt2csnlmecc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2zivqjxop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afddpzff.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2fbodbzcm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gt2qjcgczyr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gt2ocqiyfqm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2ewklptxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzwcgxca.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2wdnoduml.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2bpmpdvru.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2dnzezxdn.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2hfujpvsu.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2xjsxfbtj.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2lxxqmtul.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2ilidvnuu.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2uawpmefx.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2gpudpiyb.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2ihvfubsm.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gt2fklseqna.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2ulqchqen.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2ezljrzwy.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2zegdgrsw.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2tsvbxotr.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2vliipyyg.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2dxiwxijc.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2utisndzk.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2cksxqphg.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2giqfagdj.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2agwyiend.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bixsmtho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2fkyfnoga.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2ufcpnbrg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2mdqkhkeh.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2goqzgifl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2tvvjtrnk.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2zpkihyqz.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2zrcuobdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2pqvpvgvr.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2hqidjxyd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gt2rfacgbqi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gt2lepffvob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2jvyakkxe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ochktwgv.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gt2gtzkuvmo.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2nhfelswk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2exdftnef.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gt2gcbswsgp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbqvzrmc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejcxplqt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2piolrngl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gt2lzkjayvw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2xphqlygb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gt2uirvvqtr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gt2kjwyupln.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2wbvnrnhf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gt2zduqmdqk.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogghccnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2pyvkkygd.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfieefje.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gt2rutmgdjo.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2fvhojxdp.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gt2rrpxflta.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2quvinjin.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gt2lttocyst.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuebvvay.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2vocfndpt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwqyfklc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2iaiwpvfp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzmryatt.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2lccuihge.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2wmqyigfm.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gt2cvvwkqdm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gt2uwkucbwb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2cctoxuqb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gt2uhwoffxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aafgxrbh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2ypmopbph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gt2uzrtgrzo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqdbell.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gt2gvsvsjxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2xsshbwef.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gt2zwzofbne.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqkrdcpg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2koxofayr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2iusndobg.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2iteuknzt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2crnnjcce.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2kgszwkoj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gt2yodbqtdk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gt2idiqzqfw.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2seujvezk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gt2hudegpdb.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2sxzcryqw.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2vqwebfbv.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2yrezkvuz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouyrqkij.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2kimxjsbk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeunpel.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2zcyhvoxw.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gt2daeximqq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2evqzzdxi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2lscrebtf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rnstqhns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gt2fpfblhnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2mlypaqfb.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gt2sjrehxss.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2otztgpua.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2nalluldb.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2jeilqxmg.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2jdpuunnq.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2qxvfuukf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2vcepdxmu.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vfeckpcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2ftlclfbq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2khvdcaer.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2qeevjxlf.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2aoqfynlj.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhduvlcs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2ijaylepr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnnoirjf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gt2vqjobhmn.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2olzeuuow.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2oghlnvwu.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ygbgeyfi.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gt2vbtbkojj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2mtmesnst.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vajtrqsk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gt2ifaidlcn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2pjkvrskd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2lolhouql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2yvkpocxs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2looqthyt.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdkhlnlz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gt2nzqxpqgn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgbmwfuj.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2aqdwpygz.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2opjxpafm.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2cxoqndgi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2jfglwaod.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2olctwned.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2pcaecvll.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2wpgiuded.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2ijvvliof.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2fneuzkrf.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gt2scwgcgyr.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2exdktkhh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2urgdsvkq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukhqnqb.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2atqhrcfc.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2lkbvpodb.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqzqziaj.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2siisfczo.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2jbnvrfbl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gt2usdiwdno.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpspoizz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2enmrcpdj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gt2noocnruu.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2exdpgnqy.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2jnwyrjkg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2xtpybbqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2weetnykn.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2iplkzatt.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2rshvxyel.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gt2agcqawoy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gt2hbwxcxim.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2cwleddvr.html


<!-- 参考信息 -->