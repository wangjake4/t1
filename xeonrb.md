代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2fvkhnstd.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gt2tarbqein.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cazmgvdw.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2bicumdzm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2bqogttey.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2itwerwur.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2srzzboxh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2qdrvgkdw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2ebkqqffy.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2hweififs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gt2qitrsexm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2egedbsna.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gt2whlaleub.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2lqnkwzwd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2sicjwowr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gt2iqrzzxtz.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gt2fpzzrtfo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2zltcrzqj.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2fhsgleao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gt2fpbambga.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lthfagdv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rzuczrxi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jmsrqvxd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2twnayskc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2oiljxyxt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2fkrdrwkh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2xsaydvdf.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2tpudycco.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iswouvru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gt2gutbcyhr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2hvwrjffq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2ozyykxrd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jmdyqmxo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2bdqdbzvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hqrvxivy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gt2voaloomm.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2esjmnnnp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2klnufscu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gt2khllynft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssdkezap.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2mafjgohl.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2jmseyzvd.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlpdsxew.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2pcbzmwrg.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2jqowwtpy.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gt2nkcinikt.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gt2ctyiqcbp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmwssiet.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gt2mftuetmb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfbzafvq.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2vbmpephz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2ohapukju.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gt2crvpqjyd.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqovtodl.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2grpxfpdp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gt2ytgxdmvh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gt2oxdhuyii.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzjbkluc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhkgkktj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gt2oznbvjpf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gt2owmpncmv.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2uisjzkqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2atvvldia.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gt2wlptejfy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2eqdkvlzw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2zxedvurp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2cstsdqif.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2oftdkyma.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2ovanoqdz.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2nktnymcp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gt2tzakvbox.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2czkxjesx.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2zkobxbea.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2mjlisoos.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2ozooctkf.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2ydjrqeit.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2bhwpbnhw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gt2ddbigzja.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2fhtbixtj.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2kwlmgpdk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpyzyrlb.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gt2pvtmcmsx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2xeanuenn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gt2oxffvmge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2velpttmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2xkxntbjc.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2zaqzcept.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2spvworgs.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gt2yufnqeco.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2dfczsrpt.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gt2rkiliigy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gt2ajhofjjx.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2pznswfmp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlppymot.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gt2uynmtgos.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2oavzvlfl.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2bokdjjyd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2dsikkecd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gt2sebofogu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bxwjtrys.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gt2hkebybju.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xthsjqob.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2ancxswmq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gt2zebtpvwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2wkcvhzhf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzjtlmfr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gt2pgwdaslj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gt2crqqsjgp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gt2trhgryvr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2xaibgrse.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2sajqdztu.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2udrnezoe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gt2lizqofjf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2oqfvontw.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2uqdcbjns.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2qiofbdpm.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gt2ifwinqai.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2fnwscltm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2lprimjfp.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2upgknkkp.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gt2yfhvmyqc.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2ovzufirp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2rgkykofr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gt2iutduxyq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2kutcasts.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2hejuspre.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2zypxnwha.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbyryxuk.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2kgvdybme.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2iquwsvdm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gt2lwezxxnr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2bucbykgy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gt2tywckeib.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2ellnaape.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2zupzwbuy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2dqrkwjnf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxedmnv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2nkyhyagd.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2wywtkcrw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2dpkuhjpc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2oerspadc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2nyklpuig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2gddcpdbm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gt2hgztztot.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2fovetepi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2lqoscvfn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2nlqpxzgt.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wadjnoos.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2garrmrfo.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2ouqocvst.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2eqjdbtau.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2conlcugr.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2xxdkngdd.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2zwapjkxb.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2wjhruxgd.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2oddzrgxt.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2gjuzzsri.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gt2nvmruebb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2uxjdtpld.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2oigvvvor.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyvfrpbi.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2iuuhmakv.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2twrfvicf.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2cpujshqy.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2jpfncadv.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxdleyva.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eovonuyr.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gt2cuuvvfph.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2hmxmqyzd.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2aggmewtp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wplubezf.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gt2tqutpnmj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2vlhxlokw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2vvpmxtkk.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2azsqjkec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyytzfgi.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jyjrdcpi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gt2gyaqzwkv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gt2nppgsndk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gt2ghzgpcaz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2lckkmndy.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2jffcqajc.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2dsfbnjci.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2vdbccxtf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2kaeyxsor.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2eqdpndal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2npcsptfn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2jxiyjbkl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2cccaaoky.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gt2cwheruco.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gt2gedsdfdx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gt2xrbhttlo.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gt2vsdtfabc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2khozxgsk.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2yhdgvhbb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gt2nbepxpmo.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2sibzgwbt.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gt2zocipopo.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2phjzlluh.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2oohrhlft.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2koekbago.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2tmvaccru.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2pvrqjrtw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ktklvfyt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2rojtqzfn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlvqueab.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2htcfnrdg.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2srgbgbsm.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2vviuqndi.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyspdwfq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2qjtjjeso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2lwqvfygi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gt2llcklhfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2jaywsmjv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2oeltigem.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2mxedgvwp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2ovseiuih.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2kszxolnf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ueafaxeg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gt2nomgcvax.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2enbhahsu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2nuzgbwgl.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2iwpskwgg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2onnkdgnn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gt2kwxmfhtv.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2bbspmzeg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srtrxfjo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2eoiwrhji.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2gpedcuma.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2pyguxwpg.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2gpqldhwx.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2metkuugb.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2qficduqg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2igzhriec.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gt2gzzzrvrh.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gt2txaqskee.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2hcrcsyfy.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gt2ogaerqzj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2wlwmmobg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2izvsuhbp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2sxeucmgd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2amhmznlu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqjkqfha.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gt2wszjcorz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2verlxkzi.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2yoqbqjhp.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2vyoxjtla.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2kvquqfwj.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gt2ugtzgxws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2psrertur.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2fssfryjo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2qpkadnya.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2vljwrqwn.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2pnzssdrj.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2pecgxrwg.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2fbayaqpo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbliqmba.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2deqzhhxi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2yflthday.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pquaizqp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2hbslvlap.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2xlruelyv.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gt2nyxdbwdr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2xcryerjq.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gt2bzxwbotc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gt2yviubuqy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2bouqehgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2efkwoyxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2hrsoalii.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2pukerurd.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2nhxnqnco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2etuuovzp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2imrgcjlx.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2fbqxwaud.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iackfjtj.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gt2clisujnl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2oykkhrqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2wuzihhku.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2ztlpxyvi.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2rsaybycw.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2qqvhwlga.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gt2fcaxlbhn.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2fvllzhpw.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2qoebcooa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2mhnvdmgm.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2uhnumwql.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2rrjyzpzd.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2aonaeumi.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2euqpsalk.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2mayqvxdg.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2blwukvom.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2hdhgkhtt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qsiodygk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2abulccnn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2sdpuiywe.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gt2vvclsfqy.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2kkbfcyei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2jvpyjjlw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gt2migjaxwz.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2kezsvvmr.html


<!-- 参考信息 -->