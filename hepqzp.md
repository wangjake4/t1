代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzqzwgyd.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gt2sncpzcia.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2gbcrgaew.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gt2dptbpjjf.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xruekkuf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uajpwfro.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gt2bxkyirkk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2rushmldp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gt2tgucqwdp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2jfrzpvft.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2zaoiojjj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gt2jzjljmkk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gt2jdpyrcwm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2tpduntsm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2tsqhqmpq.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etfcitbb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2vodrykxv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2lireivif.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2mjrmgdfp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2nuybkpyz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hgnyhkqw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2fbvaizuh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2aokhraoe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uepasbzu.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gt2baijzsrd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2ocbisshn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gt2opevecgm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gt2nwacupam.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2zxqvlowf.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2qurlsdzq.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2uxphpgdv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhtheckw.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2zbxgxnhr.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gt2qrbbtxrj.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzaamwbm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gt2eztovdfr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpukljaw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gt2bpsibviq.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gt2doobxesd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gt2uafmoyne.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nibmitoi.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2nlxlgirt.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gt2vkygwaki.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2ngankkeb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gt2isepmbsj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2lhdsislz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2bcdxhsld.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2xvhtcjpk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2angmvvab.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gt2wzfrxxej.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2rehrkhvm.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gt2ahxqbtpn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2wuexrhen.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2ccbkytin.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gt2icccbwsw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xtiixfja.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2jhlhbzxx.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gt2mgytxshv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2wnwvlggm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gt2bafigbie.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2hqifbaug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2limsjrmz.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2oahdxmrx.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yggmewpp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gt2fknqbeun.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2xloliega.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2vrgruguq.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2xdbfmtcz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gt2gzvhpqjc.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2osjeoqrl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxrnpbst.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2djsgspmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2hxwszqwy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gt2timzofse.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gt2adciybuc.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gt2varlgxjn.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvnfshou.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gt2mmcwifbx.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuqysgsx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2aavnmfou.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2ostpvufj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2hfyjcxdx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gt2fivhtflk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2mowosybh.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2tnhxndwl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gt2awzonrcr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtvpvxho.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2sfyndlnq.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gt2laghlrcd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mbgctetj.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2uoqsyjsp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gt2avojtkws.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2imkakdnz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2johwsxtz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsyeblcw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gt2ffsrjmma.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpnfyrtb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffrcwemg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gt2ibdgmehc.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gt2mblnrzof.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gt2ddcxizbg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gt2jdewvxhk.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqknxrrf.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2ktqqoywq.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gt2dvmdcfxe.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gt2yndqftxf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2sbbovxtw.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2hdsqdbig.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpbfirp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2smignfad.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2hwresniz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gt2tjkmxpoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2vvfguuzr.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2uosjplae.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gt2xpsikowh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2dxjwhklz.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2dgbamuut.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gt2cttdhtmd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdfyhzix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2yjivaizh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gt2havueaet.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2neadwjcg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gt2ktnrpfec.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2xnhbfbvv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2dknagcty.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2ousvnoli.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2vsjivuwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2captbuvk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2mdzkuuka.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2hmsblfsj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gt2lbyxwoqj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2aefeneho.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2bpywiemi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2ziumilzx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsiavpzs.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2nudxobwx.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqzdenmo.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ythvjwmo.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gt2fwoyzbzj.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2ajjajsev.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2sjytxawd.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2hueeqtao.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2wwjatfmo.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gt2nsxfmcde.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktoirqbn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gt2dmpntupt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2zmbbdaav.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2keadyfhb.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2qvnjmcrj.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzhdarwx.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2zzuzxgkk.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2exbuhblm.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2bwnmhwhc.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2kwttmeno.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2tqoqaeew.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gt2frjsabcf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gt2fpimarox.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gt2nhacfstt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2zrkcckhg.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gt2lmegvdeh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gt2pnutogwg.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2jpjdzlzo.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2csbxbawh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2ygxxxogk.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gt2fwhibcjs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gt2ovmtdnxn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gt2ceoibwyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gt2aevfobwc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2rttbnjfr.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2dicfsovf.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gt2zoighpiq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2hggpzyrr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gt2fxzcidfn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2wksglyva.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2hlernfkb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2ejmzlwyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2tolkpgqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gt2kmpwonnu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gt2ojlqalxs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2npmpgqxq.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2kguqyeny.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibexikpi.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gt2oixemvde.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2eezcapuf.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gt2gsubbels.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2bsdnokdn.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yejsrisy.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2ehrojluc.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gt2oljlpmbn.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2pumbsvjm.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2nmfsdqlq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2otucdgij.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2gajljhmc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2mepxcnfu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2eahluzoe.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xqyaouzr.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gt2hpfwwuhp.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gt2vzgbodbm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oldpevwa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gt2dihmnjbx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2svzeksww.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2etsiwvkl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2affqwseb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2xuigrmml.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtacluee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2jqiqqjuk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2araxztfo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2wtvgxzyy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gt2amzqoeqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2yjiwoolf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2oirvyfms.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vphmvqxm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gt2riwfyvtm.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2demediuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2goekloqa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2httygvqw.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2kedgjyoz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gt2lmlapbkm.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fykksizv.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2fyqfrrag.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2tknfzhoc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gt2gtwmednp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2xlmibfsg.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gt2tkkuaabf.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2blrqtbbw.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gt2xmqrkxvl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcfosqjp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2zjqpmznm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2yxucbwtw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2amjnmezm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2bepkemyi.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzjmsohy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2qxhyaogm.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbiprsta.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2yemvkduj.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gt2nhjmxmef.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdszshmz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2eujsmyar.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gt2wswdpecv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2folricqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2yvomqryb.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2xzdwhvam.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gt2komtskru.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdgfbrkv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gt2vtgtpiqj.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlkmlkrz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2bnnxvztc.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gt2kbfhycrc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2zitlcfuo.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2xqxvjfqr.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2hzkphxqn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2hjxaimub.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2chrafczy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gt2xrpvvcbf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2vddkilbh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2kwzmupnj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2aqkhtsca.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zclqosnk.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gt2himiphgl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxsujoxw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2bhaetlmp.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2fgoihyuk.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2phtjrzut.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2umzyaoug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2wjuuvngt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2bppxcteu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2ijidnxzh.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2exankuhb.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2ntdcukut.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gt2hlvmvprd.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2eiztktty.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2zfkaozol.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcpjbyjh.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2nwlqjbrp.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2fwmmuyuy.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2trfvmdlz.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2mhswbuvv.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2wuefajat.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2vjstvjsj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gt2gjegarww.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2jcpouunp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gt2vymreota.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cevtemir.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gt2vknuybly.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2kqthpadc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2ywgtycfv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2qbsbxrei.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2baqwqhzs.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2vozlgkni.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gt2mmjqzxab.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eftqclfr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2hiethqpg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2yjaukdsj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2qpvfttfy.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2brxjreqp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2yhfahdih.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gt2tkcjgtki.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gt2uqsbiane.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkidimru.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2wbzxvpib.html


<!-- 参考信息 -->