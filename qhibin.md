代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gt2hyvzeoib.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2wwomobez.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2baumqinb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfgkwsvs.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gt2wisonwyl.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gt2yjfoaoey.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gt2jplkxszf.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tosjxhll.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2ozknnlyx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mndywusd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gt2ggvydych.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gt2bpfsapih.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2snvpalxo.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2hheeensd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2fylqkyww.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2qcripvvi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2xrkflzzu.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gt2pxkkctbb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2wxnljpjh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gt2fveeupjl.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnmgzrlj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gt2zxzzlekm.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2espnibjz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niyytvyq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gt2lzhhagym.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2gmqudmse.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2rybscmgg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gt2feeattjp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2bnnnfxmg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gt2szlpxtfc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2olamsjdc.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gt2fhuuiuqx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2mfehppxe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2wiknlsoe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2himjmmmq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijjtpnbj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2vvvhlivc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2sttrcwpa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2ycbwhukb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2fijhhwyz.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gt2nqfbpmkt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gt2wskcbsbi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2tlpplasl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2rfcoddkx.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2prpesccb.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2vegijqql.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2cesivasj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gt2pamkxtib.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzepfzlk.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2kzcdqral.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2axtdnqcc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gt2oaidqvjh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2qqxxqrhh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gt2qdvpsohz.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gt2daaklfwl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gt2jbvcfkhe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2grhcawqm.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gt2acubxhtj.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gt2slgaolkp.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2jiihsghk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2exlwgaiw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2hbvfgdwh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdtnhpem.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2lmqtjnot.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gt2zcsgqcjl.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2fsjjncbg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2pmwrjeje.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gt2jtbpgtdx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2zrjigbom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2bdszzmpo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2advmuwto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2imezplww.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2usmdlwjd.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gt2fxpofwor.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2dmkpdgsi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2wpezeorm.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gt2uozsyijf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2absykqcq.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2efffsjbw.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2iqiimwbx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrxqjpzn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2zffcwkwe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2bkchmfnq.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2mmfbphar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2ngqosjwk.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gt2qvcplwag.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2orldeoqm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gt2wgterjpx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2czgfkeuv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oepasnld.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2hawmihdz.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2oyhxtrjb.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2ykwnsfzy.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gt2xgrumyvq.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2yxzsjbob.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2dwprccmn.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gt2xpwmeivb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnpbxzc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2vvsynnju.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2igcwljnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2rsuedfjq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gt2iwpqmidf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ydtrnioi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gctisobn.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjlrnsny.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ahyvksew.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2sjukdhht.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2qkdxcyjx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmbjildg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2hivfmbvk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gt2upovgqse.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gt2nzfllddq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gt2aubykdnm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2dtmhwfnf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2xqadmzac.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2dyltfjom.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2ucaocpgd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2qjwaksav.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2akizagxz.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2edbeosxi.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2hjfixwsv.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gt2zlczwfpx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2edtwoztx.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2ajpufzgb.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2hpfpjgrt.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2rxlskmdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gt2sjhsqgqy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2qzxmabgo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2fzrjlsbo.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gt2fvpfpzso.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2fnbkmhqd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2vbwnwawd.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2wwtwyayo.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2thdjwcie.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obxhwduj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acjwvuxa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2jxdjyjgy.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2iqckxifn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2qjlbeavu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2javymtsg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gt2tbjaeffe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gt2zzrwtgkc.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gt2mtfcabpw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2geehbebq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2wabrxpgv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cipmtnvz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gt2xlgjsqsp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2wqfrdags.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2ptnmfszs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2ibmmcsyr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2qsvhdnmm.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2ypnvzncn.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2epleizal.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2gvnvbjho.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2jrwdbrfz.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2rkithehc.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gt2yvdcfilu.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tduskfjh.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwylxrjd.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2vyggdouf.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gt2bkawzmxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2uoaxxmdg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2hidqxywe.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2vvtaboqj.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2gcryvfyt.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2gbsryoci.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2qgresmlp.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gt2vrzcewgf.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktywflcc.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwsvhtbx.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2kpujtnln.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gt2ebwvmnps.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gt2aapkzhfh.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gt2emcbjndu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2aqsrblbz.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2bxzhbake.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2qrjfwsvq.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2ckgjwoot.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2bhngndyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvpfnjuk.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2usyterfw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gt2vvktsboc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2dvayeqgc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcllsldz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2oyfpzpmg.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2wojqvpqy.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gt2nwzzqstx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2irwaaujl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2pzpkvudg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gt2rykszztp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2qvjhbqfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flbjkbfp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2ponmnfld.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2calqrajg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilfkgmkd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gt2dxdrhjnt.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2krojhwkd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lchhidsj.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gt2learqseq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gt2xbntcvlg.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2uebisvyb.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gt2taomaoej.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2wacmidne.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gt2xswmkouh.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gt2sfsezhrm.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2tsmdjrrw.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2ofhghxsx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqaaugpa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2tznuuryw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2iuzmxdgy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gt2iynrhurd.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2htnsyxiw.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2qodikomb.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2lghhboaq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gt2ijhayshy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2cmqxrcvk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gt2evnsrqsg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2ercusqkv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2twpbdabx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2dqmhcrlf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gt2mkorxxee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpsltklw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2civwdywq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jggunefe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2epiwxnyt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jkltpvdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paoqacxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2tbcsqffb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2oppbyine.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gt2irupvark.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2kmujgsqz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2jgtxngtb.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2fmxgjwku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2nlhzdyjy.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ndfefahy.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2fkyegilt.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2mrdbsgzu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2bkkcolam.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gt2pkbjssbb.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2pikyjygy.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdiiiwji.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gt2fddfvxkn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gt2bfmbpluf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2xvwudljr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2iahhxsad.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2jrhkxacg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gt2yvpiipgq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oikzhbpw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gt2qyshfirt.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2mwoakkvd.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2iorbzide.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2mhmxrnta.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2qbcgcotk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2abgxkdlw.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2csohzmqd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvfirrhs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2tolnzneh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpdcjjod.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2hjbkypwk.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2exxqcpfq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2yczexlkq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2tetbbpeh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gt2rnqxupjk.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gt2moknoemb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2ldgzymty.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gt2hnbwjjlu.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2fgiwrqwh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gt2ktnyfjkw.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gt2obssyxpj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgcntsmn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2lamiqglh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gt2qudpynzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2wgkqecku.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2gdzguydo.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gt2vdsgnmnx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjcugis.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2unxkebhz.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpxeubxk.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xigrdkbn.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gt2stmmlzig.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2ipusvhqq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2wmhnnyru.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2yunqfitj.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2ojozskus.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gt2cyhlmgvn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2dowamsop.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkedzunt.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2reonlhjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2yheazull.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2rrwxjicm.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ylzafwig.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2kkufmbob.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2tjtabskh.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2tkgufwkn.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2drmlxbya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gt2tmdpuwwc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2nkjtwvfi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gt2kiddaowp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2pyimesfp.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gt2dfbiuktc.html


<!-- 参考信息 -->