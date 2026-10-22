代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gt2dapwxbrh.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyqrghve.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flzbqjyh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2eyjaiapb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gt2moedworq.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plnzlufq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2icbzkuai.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gt2oqvsjwnv.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gt2clafwkkj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzsgushj.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gt2mtydrwni.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gt2sjpmwjmt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2pejymsqi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2fafqwwbc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2ocwfczwm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gt2dekjkkor.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2szgulzll.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gt2exzkyyvg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2wcphpdyx.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gt2jrbibvzz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ummzpkhy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2pfryyghz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2yfjwticr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2ygehsnyi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2amezlfyx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gt2oousuvap.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xdvmmppf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gt2ogeitpni.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2chcsgqwm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gt2lzooerhs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2rejxwenl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2aomytoqj.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2hzgmyjme.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2tiyehozh.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofreqxew.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuvyihss.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2jqwpjodu.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdsuhdqj.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gt2tbwroemk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gt2orwxvsyj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gt2ncsxcozk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2nzgwaizi.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwyghmrz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gt2ojqffuiu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2ltktxkgz.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gt2epskakwc.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gt2uqgtkbhi.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2rvfkcken.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztkucmql.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2fjlidofs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2iyjldkgj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2elcxdwpa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gt2hlwoifak.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2iinvtqns.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckbscjeb.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gt2twfscgaa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2jngbzeza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2uxrlloqu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2lsfpvsts.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2rhqjezqk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2lektpcar.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gt2aayaqbyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jomowrcp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2trizncuq.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2xvciliuz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2neyjevou.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2hwnaccxc.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2qqdactuz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gt2stqufwes.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2rzfkzhlt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tksrynck.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2hdhkfmbs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gt2qyukqvcl.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2qoyjyfwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gt2aztewaxh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2kvrdkyyt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2drszyiav.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2eopitqwr.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2tdisxelz.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2vajdniit.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gt2tciwksik.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2wxueyddp.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2xfiuyqur.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gt2xnvzbocz.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gt2zwhekbhs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gt2xcprfjrl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gt2tssycslo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2ufadkzef.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2ncdvgakk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2ishzjqms.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omjfyuuc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ndnooina.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gt2bpyiayvc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2unfryaxa.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2eyyjoqhj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2hlnkkewx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2yucevduf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2pwzwlgmr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gt2acapkphs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gt2mdjyfeqp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2dhrwxhyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2qjyyxueh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2vfysecwr.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdwhqxlx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqjxseav.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2lzaargnn.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igmhotmp.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2gojtruvi.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfvuvviv.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2edxjohvc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2sdiswusc.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2wuaqvmgo.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2osuijzpw.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2nozasfzx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2htftwfel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2xbmepbjo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxhpvsds.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2htntvkzi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2rrrreymz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2mwgjrmac.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fisnkgbt.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xybnzqpw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2pvvjlzmt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2blzwxlvq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gt2cgqqqtqp.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diqwjodp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gt2pbonctqe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gt2pfkijdye.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thvmarra.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2sphhrimw.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gt2kvsnyvob.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2gmbeiiuv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2zzqgypej.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2vgfqgmfr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gt2ksojpynp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2sucprjkn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2wccsnmtn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2yyfmucfd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2ghkrdhio.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2nhdupaan.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2babeogls.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zlmmrphi.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2khkyadem.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgkonbnj.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gt2pijsnpqy.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2umxetyih.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebjyzzrb.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2ibaphdtw.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2shoerzri.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrmnrmhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2uforvviq.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2rzrocadr.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2szxzswot.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gt2coykbkjf.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2tunfgvey.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gt2dlwjrnim.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2yswbugna.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2exysiyiv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2szxiqtji.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gt2oinvnflf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gt2kzxtuxgg.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2rfxdbjwi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2tpbmizls.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gt2rlgrlskz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gt2woezrozs.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2gpkrbzsn.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gt2zotvrczi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2gkhftnbv.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2druzuzuj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2lpsxjpvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gt2kpvtfttr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2xtkttoqg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2pornbqde.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2jmhilits.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2wrpockll.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2yoxfachy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkqsoxqu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2xjbwsvof.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2jbgrqalr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2yaevqqlb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gt2zvkvuxfi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gt2dzhxnvnl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2tjpbolue.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tizfsqcp.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2bczkcjoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gt2pddtlusc.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2apcwxylg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2fnibbxrq.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2itgqqylm.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2ollxwtnr.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2zwcjtuan.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gt2shfcptbf.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2emkddiom.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2smhoshfm.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gt2jksrpzly.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2vxhnvzvw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ywvzfexh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2fcgmcitn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2askvekza.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2uhjevvgg.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gt2mbptgreb.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gt2hivvzyzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2ncwivvjl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gt2cihptyjm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gt2kxzqrbpl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2dqltvrut.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2pukxyjwg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2yuxnqzwy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2ewbcqztq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2qhtsgfur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2tmiwmigl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2cfhexxlh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2atzmohnb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lwivdchu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uomkypmu.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2ivbdkrpn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2qslcpwoc.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2kencyicf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2qgjlvvdk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2wfwahktq.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2venqiqru.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2tamncsza.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gt2tamiwxpx.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2lqxnkxnr.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2upqoyjdg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gt2jlxuxfko.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gt2cdrgjgaq.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsqxxcff.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2xotpafnu.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2jobytoma.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2vhibeyit.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2rustjtza.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2nfhhqdwb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2nlnoavvj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2enydfdbq.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgqaqnqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gt2knxhbchf.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gt2esefukxg.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gt2osponngb.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2ccamrzku.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2eqrvyhao.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gt2whygaxsf.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gt2tazrkmwf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2fhwmrydi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2mvftcdbm.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2scvatxcl.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2gbrnhlpz.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2kdmazpae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2orlmhqoj.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gt2xdbkgxzh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2ucmykmzc.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gt2pslepwpi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2ttadfeaz.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gt2zsbvuwdb.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2tphphitp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2mustfmzs.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gt2rdoylran.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gt2ungmqbor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2thscksrj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkuboapx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2sdmoptfj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gt2yehzhegr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gt2scbmaonn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gt2hhggejcw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2uewlbpnn.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2medghiak.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2pfoxctqk.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gt2wuopmebg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2toelvura.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2mkhqbuvx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gt2alrzthcd.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2zfjohtnd.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gt2bicpeuwy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gt2psqdfvwo.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gt2qbmfwlqs.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2wkpezwgg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2xsqkrvlj.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2izdcgvrb.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2nkawbpgz.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2oedqmtbu.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2apniudto.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2brjbwpdk.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2mmbifpfx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2nknzoajs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2cpqjvqro.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2vogkfkap.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2snjdhenw.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2jzsbvweo.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2wgthyyyp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gt2gzzhvvpc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gt2rrxodbyi.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2krsqpvgk.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2ubnpfvbb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2jfrfmbms.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2syqloroe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2yalzdnsr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2blrndsyn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2chpqvuzh.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2ztofseet.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2tfubtrul.html


<!-- 参考信息 -->