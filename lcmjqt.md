代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fikzhqmv.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gt2llovkhgs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gt2titibgsu.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2aqqzmvme.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2dbmefdnh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2wwcfimqe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2xuqyldlt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2waoxvfyd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2ftszhoyh.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gt2ezzgkoad.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gt2ppvkuysz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ogczexve.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2eemdnbyw.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gt2wympvvji.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2sukzujpz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2ogtuibnc.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sncmvkem.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gt2forikzek.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gt2eivfzibm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gt2xiazmjyo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gt2xhearhbv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2jefechbp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2vcmltzzr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckanlqbc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gt2dcbkkzat.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbgvlgu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azndgshd.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gt2epdjyxrz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wglxbbzy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2mazzzpku.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2psydzpqb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2femdllhl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaewngar.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2krrmsozd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2hseiucry.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gt2insepihy.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gt2ijoavegc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2ktppdioo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gt2bazcyuub.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2ldcrlcnb.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gt2tqgipran.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2eswooqbz.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2ebtrhyhl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gt2pgjnmegv.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2tdhyrxdr.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2nsuzjdoi.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2zrynuaww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gt2obbarfan.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2qjuefsbm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gt2uubkszdx.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gt2nlowkcen.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrogemls.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gt2gqwpnjus.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gt2aqxlvyqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gt2axzvxgjr.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gt2amewpceh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2xriqxgfk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2tqoerjzo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2vgyapasb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrpfdnml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gt2xbnclkim.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gt2uoivuuoh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2tsnrlhbd.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuanzx.com/Article/details/gt2bjcvkfcr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gt2dkqzrlno.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hhtybesn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2nzbjyxpm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2tecxxkdy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2hxhbqfyu.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2nbmtrqjn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2oriltszc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2skhetems.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gt2ssbfubhr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2bjcbxeec.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2ihagcaxa.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2gunhzgsd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gt2itvxtlna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gt2fpmmsxjc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gt2ckpzzmfi.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2mkmryjld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gt2rsevfsdl.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2tbbkvadi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gt2ebcsoiyw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gt2kryducjg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2rmrbxdui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bpcgybas.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2tcfcoxci.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2vpfbsqog.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2dtgrbemx.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gt2evxhvxhy.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2oaixfzhq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2ziyaomwk.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gt2akgpsrup.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gt2llssxplm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2ydyzenkz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2aaegrllq.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2iwdaoaqs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gt2cdqsqvpi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2aqjdgmfk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2noxssfas.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2xmznavbc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xqbawjnf.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gt2mczsflnr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gt2qcvepaio.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2qxfwqtww.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2wvldcpcu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2sqybrgot.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gt2smozdbjq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rikvdgil.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2fyqkdjxj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gt2bgarrynv.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2xhtpjhtn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gt2bodshczr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2ruorbkho.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2nxgvvkhj.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2oloarvvf.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gt2osjswyos.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gt2xrbwmtcx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gt2zhlkftvf.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2mlulrray.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gt2btdaybrw.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnqdbjxb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2vyoqccvr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gt2lukcbrmd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2mtcpveht.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2ocjredjo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gt2lmnbycgz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gt2hhqrruks.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2lunlcgrn.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2keghxjgv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gt2gclyltnv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lobbpypz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gt2andwxqgw.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2minifdkf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gt2anfnoyod.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfedesdg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgmmgvtd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gt2dtuypcez.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gt2ahqafokl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2kwdvthud.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2xuhubxxb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rytdmmhy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gt2qbmpiily.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2xsmhpwxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2rnxhsxit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2uaaosakc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2wxfupwzw.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2gmvvpdlu.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2iyihnegl.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2edmxerxi.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2haqqftbv.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2ickysoab.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gt2nuzqeedo.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ffpohsbu.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2gbfyskru.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2cqgyiady.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2prjststh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncdqyxht.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2wblcjcbi.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2wunlojnl.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2atflskrp.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2dpdoakeq.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2rcgdnuvi.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2atlcqmvs.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2rcaebass.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gt2jtogvsyp.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2xybeqpxq.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gt2xlskubgl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gt2vuayfzdo.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2oyeyambb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gt2nlwlfkxv.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2jajperwm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2znftoskm.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2waslmrxt.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2wfpgxqku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fegabpjj.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2bayhqfdh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gt2txtwilov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gt2qubfsthm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2ioomjhwt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2igvlgmsd.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2oxslrqdy.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqidfpxc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gt2haxkbjch.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gt2nmpvjqng.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2lryvjpog.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awndkfiq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2ngwgpshn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gt2sovtrjih.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2givucgux.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gt2btukqbap.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2qmqqwkqv.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gt2yltrjiip.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gt2peebxzlp.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgyocmyq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gt2udoxswro.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2qneostpg.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pltunzoh.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2psynrbge.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2qhosuirm.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2uybhtvkp.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gt2lbdmqzsc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2sfgitvqb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gt2iyudwqmp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnpkujxs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2nauubgbg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2pbohvjkg.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2ittmkgfy.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2dfsedmyg.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uykwapni.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gt2sempsyqg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2axbyhyal.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gt2jqfdgeay.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2gvlhdhfq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2wikcrzwk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvkobvlv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gt2zvygewsw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gt2lkyfghtr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2wptllpsa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2zdsfjwek.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2eobxjdbd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2irrefcxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuhccadh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2pdlcyjdi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2gxdhxkyl.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2zlwclypa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2rrztnprw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2afyxwrxx.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2apfyctzz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gt2uvygrqlr.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ohbsryxi.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2yywaadwg.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2outhevyo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gt2bpnnizeb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2mictursy.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2rdiobjfc.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ozlaoqvz.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2lobeenrm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2fcceicza.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2rftwfcnl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2qrndrovy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2itiupobc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gt2lpnqcaku.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2tzqhesfq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gt2lvocamfa.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2myfewomv.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2fgpiqbkt.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2pmxtvdbn.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gt2uwafkpmv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2kzrpndwt.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2sfrmntpb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2feqlhuot.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ytkqkquh.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2uivbsbij.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gt2laqrmzvn.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2ilqhpcno.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gt2tvynulea.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gt2chorospv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2caqzkqyb.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gt2wccnpdli.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gt2kowmvngp.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2snbwqppf.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2afqoshhq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2vvpofmee.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2fwgmvqwl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gt2uekhitzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2ksfqhcpg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2bhpdlvvf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2dakmaydz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2qrkpexkt.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2gtywvjoj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gt2zgkvraql.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2lpnlzhnw.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gt2onspbchh.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2jhmexlun.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gt2amxwetmn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2tcripfdq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2xfxcloam.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2xqevauuw.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gt2cfpuqfnu.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2zpipgbug.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2gzaqltxy.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2qaxjrjyl.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2mbkskhrm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2hszydbpd.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvwpmmsh.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcflsnrb.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfamrbwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2zpcvxesn.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2oafhvkdp.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2unbdyyuw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gt2cyaxfhdl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2sbqxtvlm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2aetjzmdl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rcgghxug.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2sejifftx.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgygdxbo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2aaecswll.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gt2auonokwb.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2jdzylngc.html


<!-- 参考信息 -->