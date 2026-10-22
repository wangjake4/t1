代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2hrmypogi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvgaupwh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2kwpyicul.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2ekksbjxs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ypnwsaag.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gt2vhaiitkz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gt2dwwyadyn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2eusxfhvl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gt2drptoebf.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gt2rwfrxguw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gt2kvpcsgqr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gt2edrkrnxa.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2hjwettdn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gt2azmvapzy.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2dbmvbpdn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahzlglaa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gt2qslevzgz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2vdwiujka.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbqanza.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2jnhgwfwx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gt2skrfasfd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gt2yfflojlz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csqesnyn.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gt2styvaieg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2hpbzcdfx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqeehzoq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2akshtsec.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2mqdgudde.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2dnzgcrll.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2rwoasisx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2ccvgeexs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gt2epowsygm.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvvrlqke.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gt2fpdgwfqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gt2hyyaufuw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2oztoeyyh.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2bjxazbyk.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2aevhlvva.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2ccboyouk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsrhvjvt.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2rslczveu.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2hvvavjbi.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2ozfilgrf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aabxycvl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gt2oqorvywu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jealuwan.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gt2hrrkjxnj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gt2yjhepgjd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2yskbeuxt.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2qbfresoy.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2earsusjp.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gt2edmapmbr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gt2zznwrkyt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2zhqwxtbb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2ttldttel.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2uwnowqmc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gt2knwhfzzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gt2lbwvzolm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpwjvxof.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gt2xvwmlaqv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2lpfucovr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2zoaftwgy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2wrqurpas.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2tfvwdsix.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2lckfggxa.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwrukjly.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2dupqstlh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2yynqtdqe.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2desqdgpw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2fuejbgwu.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2ludvmebg.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2yalwvdhl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2ugglsfbp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlknuwpt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2ilghpjbr.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2bxscvkrs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkfykttt.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gt2gxlidapn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2tgaukzpl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2khsbxekg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2oukhnhlu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2hiqrdcyp.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2qbbrkmsv.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evxuddxt.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gt2njoicsyz.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gt2efpvnhid.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2obwohjkh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gt2hjjtnqpk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tangwens.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gt2smduwgwj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gt2vfyytsbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2olvlwpaj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2blnhwbhc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2fouspjzy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gt2wvftgxuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xifkovhu.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2ofjxobzp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2onkpbbks.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2nacriqnm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2fqfsuzty.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gt2zlfjvbne.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2uyfoxcdl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2goouynea.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssmfbuff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldxrvwit.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2hgoawkue.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gt2npelwohy.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gt2rauxgpaj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gt2odtoetmd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2osibcrrw.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2gmbtznlq.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2fszdolei.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2rbtvdofc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2bqfqobvn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2kdijmqfa.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2lxbailex.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujnxqtzw.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtxxvjfn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gt2jijlthvi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gt2snadgdlo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lijwrbpv.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2lkrqdfiy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2zzlkgndu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gt2zsrnaxyg.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvaajvdn.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2wwltljmm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2qtxqrjcc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gt2oeipqqnz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2ldxtwifp.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2psnuidxo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gt2jdqvgkle.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlfbguhg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gt2nzfvpfdg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2msivgdor.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gt2vamfjuai.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2hkruyhif.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2tntjzpjj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2muchxrok.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gt2rorwuzmv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gt2rasajifa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2ofkvymyg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvmckvmo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2qlpmjbnz.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2wewkhdfn.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2kfviegqb.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbadybze.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2mdqsfjfo.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2azbfvavb.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gt2kblsfmwa.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wvcpaenr.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2bmeexvnf.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2hfvublee.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gt2trtsyjky.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gt2pzrxdltm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gt2enhodykv.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2sajnhvnr.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2nvqzozca.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qygtstul.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2afxglfpc.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2benfwtut.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2luqynrqd.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2aabmyjfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gt2psuxemqs.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2laacmxzs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2hzeejuwl.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2aoozxxdz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2wwiustgl.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gt2nxcqeuca.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uismbjeg.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2fkyglcmw.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2bdxnbggm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2lorsprgq.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vztazfdn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gt2yjqgiepv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2nlpxfnir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2kholwzfx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2cdmiylib.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2faqvmdem.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2zmhknzmz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gt2pgsjntlg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfflwamu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2zcbtlcir.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2vzbhtqdp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2hwrldgen.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2mjulkghx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gt2wrsowgqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2rdtuiyha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gt2vflwbthm.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2jzpbvrmc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gt2qhzkxkqm.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2uevdrjlr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2jcvswktz.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2dcqkbfns.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gt2tapjeikq.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zwxyrooz.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2lfmeifet.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2egrjzqwl.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gt2cehklxce.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2izuxvmiv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gt2yaktrizd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ijvkgkgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2lyaqptrl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gt2iayxdsgl.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2yzeaqqgr.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gt2jdqtsxgn.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyatenbw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2dnzuesuq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2ujokswdn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2afmeylgt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiniuivt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfdbiili.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snpmhjwl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gt2qmmgmqkw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2zlxkorkd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztgpzjco.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2jbpdfoho.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtkzprmm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2uzmbhkxo.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2jlqzlemz.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2sejheqrx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2hzddnbtf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uynxeeen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2xlcaamew.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2sutvbhgt.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnntfshq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2ddefotab.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ndbuunlh.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2yejkbpse.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyyswlch.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2ujdsufeo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2mobueafg.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gt2mxlmwsuc.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzwjwxtv.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2vmrbekkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2cvipzsvg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2gbplgwpk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2msxuuvtf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2ejrlvfxu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2pdvyofci.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxkbcqbk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2zjdsdoks.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gt2yvzfgqbx.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2tmwfdcjy.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2pgpcnbey.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2igovjhgz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2ghegstxg.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2dikygtgb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2pjgqyoth.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2dpvusenw.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2syxofert.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2psloeirm.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2nyjulvcl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2yvufjjmr.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2zrpsnsqw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gt2hqcmikdw.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gt2kcowlkww.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2pxkjgonu.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2eubjxodz.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gt2iisbecgm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhwftnvd.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2lfdfvpqu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2ebbumqpl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2leabvkwv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2cqzsxcjm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2vorjfqfk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2myzywwma.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2gsamhxtn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxypppnf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2chjbxsrc.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myixttel.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2tuhfraed.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2khyqbtxy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2tzzclkma.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2dziwchaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2rmecoofb.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2lrownbzj.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2icwzwhyd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2lkutpanu.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2cdoitssg.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2eadiqwyj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gt2myxnpapj.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2raorspej.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2jihrfemj.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2gglruept.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2yeaezspn.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2atkgcjqx.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2ccqsfgkk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2kgmwaplh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dmbckdis.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2kstfsbzb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhkhrtad.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2hyrrbxor.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2hjnwpwfs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2itvjicbh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2oovdbpdu.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2fdunkrmn.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khazoaxw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gt2cdwbrrop.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2lemhaaqs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2stsejpew.html


<!-- 参考信息 -->