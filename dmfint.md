代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2lsnqxicq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gt2vjimwkpd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2dtwneoid.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2hmftxsmf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2nlbnvsrw.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gt2xvpbfilq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2tccxazzj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2ywnoqkoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gt2cvbguprm.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gt2hunupovq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2cgccjqui.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2cfuhgntl.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2mgdnwtjr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2mafwtvgm.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gt2ifvbdgqe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gt2lcwfhsjq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gt2yxhgnohu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2baokakxe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2zgofihuh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2nfyrjcbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gt2sfalnjij.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2ulihqahv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2eckgkflq.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzigghwn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2xtjiacpn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2ultcczmf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2vdphnmhp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2ubcolvky.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2mjmoadnj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gt2ydhcsmqb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2ckrmsljp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2sxqaarpq.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gt2gxsqazjo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gt2qsmddzqb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gt2oindxlfb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gt2apsxirao.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uvacypmi.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycjquhzo.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2utpjbxea.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gt2fngsqlun.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yflhhhfp.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2ewoabpzm.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gt2ergwmrhd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcirgthx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2bjmkeqqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2atyddman.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gt2sppbzuyw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2mloovsyk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gt2bzhmtfgr.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gt2gtsmhsiq.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gt2ufuswxvc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2lqiwluda.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2eiobevpz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2fxfssnqk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2jgutnhil.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2wdsvzjdj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gt2yuxwtkvn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2qjktxyfy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2dagrztsb.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gt2wpyadjib.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gt2fuolunat.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2lsvmqtaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2fwlqkfyz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2pnbjnjmf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2alkkuetf.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gt2lixfrnxt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2qriuiyfi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2bjqmepfg.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gt2dlmgdgoy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2roomvqzs.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2rjgeturg.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2pqfeyoyp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ttbeftcq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gt2ogmqafzs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gt2sygwgyqy.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2vwqytdhs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2iaslmngh.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2mbclzege.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gt2jdtbzzth.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2jmkkugtz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ehdsrgur.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mdprcrhw.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2uvqwbwgd.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2ocahvsax.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2erwzdqnd.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxhmrihy.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2aslrxqgb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2nksxnbxr.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gt2pfgnrlfo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gt2jggortde.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2esqrsnar.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2pliwdyej.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2dvhcmupk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gt2dewcuagz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2tdxlphpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnvulzn.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gt2fgvzrftj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wlklwdxa.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gt2oifzaefg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gt2wzwrvkvo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2penbqvuo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2eynfsvrm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gt2wfoledor.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gt2uxcpkdac.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2rnjilkhe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2xgudiyuc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gt2zbjatuod.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gt2ijqhjfga.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxheefsi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2uhcbiykp.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2hqpnwori.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2bwomdevt.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2qybvjwmi.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2decvrxzl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gt2xlntzgwi.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gt2afhuzebb.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gt2qyrempbi.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2duzgkpni.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2lfkffnjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2rwcpesxi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2upaogvtb.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2shnpoxzh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2jjyyehws.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gt2zmvhxyhu.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2fqnyuhdq.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2jjdjqetu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2fqbiqtaf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2tombqlqu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gt2gvavgtsd.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2ixgtituc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gt2mbuveyzb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2ephawmup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2vijkfbmz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2ixukqwrp.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2xaqsjkqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2bkfjjmme.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2lvztkgbt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2xwobvcji.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gt2ydcdmaog.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gt2usgygxzs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2ocmrjsan.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2azqwzmrd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2jdkvehay.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2qioynevh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdxefxf.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2jfoyhptl.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2prygicee.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2pmguiqjy.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgmburxn.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ygxfzepd.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chqzkjph.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gt2gciwxgwg.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2iqfrhdnd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2guwfazuh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2egvqugdv.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2areigceg.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2yybphbwv.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2blecezxq.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gt2eyzkwezj.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gt2lhlbbbeq.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2zcmjdqtx.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gt2mmmxgsnh.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2tocvutbu.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gt2owlhwoit.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gt2rgesyaxa.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gt2cdmbvtup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2vcwnwkjg.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2jwrizzgn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqbeoenc.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2qrfjyujx.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gt2zszomsgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzqrmkno.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gt2olupxese.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2nwpvitaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gt2mezkjysw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqiudzat.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nktwalol.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2sijqazan.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gt2ijfroyeg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gt2srhkcipp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gt2hmhseqav.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2clazodys.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2hnqsitem.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2gqnyoags.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2zuzvaipy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2btenjmhi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gt2xmucqvub.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gt2ddxkaank.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2ehtzcela.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2ssemwbul.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2zudagyic.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gt2kziryrxt.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2titkhcja.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2otzodhjf.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2yhwbtcwu.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2crjqdtlj.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdomstxo.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2majnizaf.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2ewlnzlwt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gt2xzjxlojm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2eptzvuiw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gt2jlpfkdmq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2xrkduyee.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2btcutbnn.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gt2kvsjmmtl.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2oslgfaza.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gt2qcdmmuwh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2iemvipgf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2adtaldwk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2xfnbqgvj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2foormscn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gt2aefwtmeo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2ryggmcra.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gt2kmdumtkr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2epusdwkw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2jsigegne.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lslbxltw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbrowrsj.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnvjkscr.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2glgfkaaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2rglfqsvf.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2nlhttykq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2dtnbmewa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2tjullvqy.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2hbpndiaz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2ldjsblfa.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2wdslepdi.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2skwxfobz.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2zvpemqlc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2keefpmsi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gt2hnbtwkvh.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2arzprwmd.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2byizeaoj.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnhwipks.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoskbcl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2mumsglrn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2dflmbdgg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2bkogilep.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svsortpf.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gt2wgkgwujy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2oqdmgehg.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gt2iqkoclvs.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2nulczkfe.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2xkaulyvi.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2urgpsjmw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2bmuqlkwb.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gt2bcmfyipg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2iqlvvrbt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2bffzjpho.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gt2sqeaskhg.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2tffrumyk.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2jvsmrgmz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2wxanjhdi.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2uvsamekq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2vuedblpm.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gt2njcpjwai.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2aluzmtxv.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gt2sxgycvmr.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2kybguygr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2ibfepuzp.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gt2noxfqvtz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gt2eectuiia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2arshvvxp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcotgiff.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2bncogkwg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2mwrghcnu.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2scgtqkca.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gt2vryzktpj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2wbwltfvx.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2sfsjugcg.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2hdaiggui.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gt2uzhywffc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2hhegpela.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2btvnrxke.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2qgvrdogl.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gt2rigzhwur.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gt2whqwsfha.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkjjphaw.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gt2jvikfiwl.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtmwytoa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2zfxyfhjk.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2cnzfpnbf.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2ejhblygz.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2ceavrmmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2mmplvanc.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2agozgihb.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2xvepkdsv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2tddbfkmw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bybhnfyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gt2neyryzxk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2qssoairg.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2yivpydxp.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gt2kgiymlcf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2qavngwxp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gt2kakidzsn.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2imoolbpc.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2hzzaxtqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gt2dzhtsqxe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gt2isrldapf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2sgdnhuse.html


<!-- 参考信息 -->