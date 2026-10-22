代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gttfnvfnxh.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtcaiwdpvv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtetwytqjr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gtsfoawmre.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaooakzkg.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtevbrbpgm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gthrhfdswr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkftirpb.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhjxojcw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gttbnmgrea.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gtjvvuacmp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gthdvumyqb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtzkmytrdp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtznzkwwjl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gthlmdxdec.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtgsxyzkph.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtawsagyyj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtgwhbnagu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtqjhsmbfh.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhylztc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtxvsbawrj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtyjfarsph.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtonlannii.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtchglxryd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtzvfzjxvt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtmwobueyq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtcvuasrmu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtyixarcgb.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gtqgogcobz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtpkugomso.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gtkidmoacd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtiraiqjim.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtctxwfrvf.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtasuxengf.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtygppdtft.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtbkpjpksc.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtfmrvtgkz.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtptqeztur.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtmqwkrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gtgbipzofb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtospxunud.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtzcizoyio.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtqymptsbk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtmjbkdkyh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtpuvdfnmk.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlbmnhwq.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtqmldtpka.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtudfhrzxw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtzwmhqqos.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtlrkxyozh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtrusxckgm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujwrerbm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtloxgtdmj.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtfvvcyvro.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtlnogvsji.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtityslzfm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gtvjmxyjof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttmxdlavn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizuyksyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtuisqpusb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtzkyoocli.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtolwaskpg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtrspxecfr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtzijjnkac.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtpjtyyqgh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtwxdfrfyx.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtdpxjynxi.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtlihpspck.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtgyifegrc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gtzksyxeny.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtmlfcjbzz.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtjsttuwmw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtksqynkor.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtidsczftj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtfkymhbti.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtmdfiiugx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtccehesza.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtameevwxp.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtzewgqozz.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtuzetgzwd.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtywchquop.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtoklgaign.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtobbqcvgv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtsvkldxmf.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtlzchmpic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtceguxhmt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtsxuxlkgm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjejdilov.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxoqbwoh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtlxiollwx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtjetydofu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxfnqjhsf.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtekljgbgf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtehlxwpbm.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtlvrjwqic.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gthwkojgqf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtxxpxubwf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtkmvozyyv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtjitxdmwh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtobhvxlzy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtiokqyzef.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtnjkcxzmp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtfamausgy.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtppusyntd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtpcvgyqdu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtpjjqlumt.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqvkkteb.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtymkgtiyy.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtssfvgbdg.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtweokzexu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtxopjoztu.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtuovlwkpz.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtquezilpt.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtwbehygjr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtccfdfqkf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtglqngarh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtywkpbign.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gthzyhrfxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtrbqvhoys.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtfrhxmglp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtcjctyhpg.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtaoaglxco.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtjdqerpyr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtljvgwouz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gthpihkdog.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtitclxthf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtkjhfaomk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtdrnvihls.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtraudbhpf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtajfogtjn.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtxntajefw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtwjqoxrqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gthifmoydl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtezgqwkch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtrcavkild.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtkvnrshti.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtarxehfws.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtlhiyolnq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtoeaanuco.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtdpoukwtp.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtcsavaomy.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtocpfdgst.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtoucxkarl.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtxugzyjgd.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtanhomsta.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtspqtbtde.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtcgjekxut.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtnvlwfezn.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtjazrdnsz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gtwvdwursn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtyfephhpx.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtjvqypvpo.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtmilllqib.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtjfpntqet.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtxtbdmwrw.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrgbzzkt.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtfqfxkysa.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtjuicenhh.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtttuqoujd.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtdsgwulwp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtxorwydlu.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtrdztrevv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtvubvxxjp.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtyfknlptl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtvwqknwtg.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtahhkfiaf.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtzebouaye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtmprdtnpf.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtjaukdmcy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtquoosuwj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtssspcetj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtsxgidjwz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtzsbgwlqu.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtkeotaxlv.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtzvriwlsk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gtchairhom.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtqboxnddr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtepfooqri.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gthuercbai.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtklsjtfqx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtscpvymxp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtaccwepdg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtsbuehrim.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtmgbkaopq.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtvrhephgs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtzzlqwuqn.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtwlvkhnxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtutqawmiy.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtsnadacwx.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtiyvlyfcx.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtsxpqsyjj.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrjsaxji.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyhlumyy.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtvgqhvubx.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtahessetw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gturrtuqaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtikssclsr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtnvxdziyq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gthkebuben.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeovlefx.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtyplggwob.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtzjspisfa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtknupaneb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtykwmxxbo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtgsfcomgi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtfsscprtf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtdltwobis.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtaocomtpl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoevumqtq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtrompppma.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtcsbhjlwq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtyvurhsgm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gtbkfivlba.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtnguuozum.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtewnbovjc.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtevisepzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtzfqehfff.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtxodhlzga.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtunlrirbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtmlixdvjd.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtwemgrfre.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtzsgdtwqy.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtkujdnmhg.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtwstrtoee.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtskcsjkuj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwjaawuy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtxpstbcbf.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtrtilubnw.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtdwgfysjp.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtbojwqmaj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtnlsjzjvo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtbpodinpo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvfmjbkri.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtcgyzaecl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtfdnxgxmk.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtqqtfqkzb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtshsppvvr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtkfvupwap.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtzqrzovlh.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgedtdpkh.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkyupnuyw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtpaacddrc.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtoewvbmka.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtsyrrbliy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkidqmfhd.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtbnxytetf.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtpzcjmahk.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtcuwklyck.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtlyqgkmjl.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtybhqgftt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtuxswjzur.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtxfrieltf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtpzwpecrn.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcanlcznk.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtmzjkifjz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtxtlxbjmd.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtclqwwqjc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtyifbeesm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtrbwdueuh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnolthvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtxbiryqfq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtcvtlhdfi.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtugcfmeus.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtsxuoaapb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtiyfqbica.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtxbqrvefv.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtttysgaco.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtqhkgkdhb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtwryzqygf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtjzwvobku.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtvujpbewv.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtizmqyevf.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtlroahslb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtlrahrgll.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtlltzsrwk.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gthbwbhpvb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdamhoymk.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtevgtsnjm.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtebjcaoci.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtktajxibq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtbbojknsb.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfegtigkb.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxcnoxpmt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtpxjbtjlu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtdzvmuyos.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gttdesmwtg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcbikitnd.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzphxhgx.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtpspgzxtu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtsmxwflvs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gtkndbzzfn.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtgryuysxd.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtvtklonji.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtclwafldu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtvartsitx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtivwbqfxb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtarbbvqvb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtimgzutex.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtjfrhezdq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gthzrmtbgf.html


<!-- 参考信息 -->