代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2iwotojyz.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gt2xovqdtju.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gt2wpmkiofj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2pmqkztbj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gt2dcrvbebk.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gt2ooeapdmb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2kpisncdq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrkjqbfp.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gt2cxkobgun.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gt2tueixpsa.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2edklkiog.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gt2sfplgggb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2sznkmntn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2wfpctrce.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2vwxdvevm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gt2emixpqqq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuacaxew.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2zxpkwbyw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2hvrgdrfq.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gt2vacsnjak.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2pzrlagte.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2vaimrwzg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gt2ipzyogxi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2kxqcxrpq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwamdbz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2lrvlyktw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2oqoivlvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gt2nsxzyzsz.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2ytcuidaa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2yadzrify.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gt2pmydohqj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2sodbrgga.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2aegcvzkd.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2dzxrlgar.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2vtylnbbq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnbfmjhz.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2johcxakt.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fainbsok.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2ckfyfndj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gt2sdlninmw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2xeeawvpc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gt2pnepkznq.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gt2emrphpcf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gt2awosbzgy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2qrevxowl.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gt2rhtahjcp.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gt2xlxdrgcs.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gt2jvxwrofs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2xmwlcnrl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2axlxlucs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2aheeudry.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2pqsipnaf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2shzyyomq.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2samuvuht.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2garjilhn.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2tdwlpkks.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2mylqjsmu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2auznrqzy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2ctznlacu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2qyowpqfg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waggwllj.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2urwekrab.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gt2dcymjdro.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gt2zapxcoqj.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gt2tcaquxiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2tfvuvbsd.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2wmplabwz.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2rjabgpgg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2gcxrsgqj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2xrztwjlm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gt2khmzceig.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2uynmmuho.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2wzywqnqg.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gt2qmzgiqab.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2jrjpcbat.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fztwgouw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2imaizlim.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2pktpcrbm.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2vadrzikh.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2kcfpdjej.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2scpheyde.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gt2qxxldjvd.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2kpvetvmq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gt2zsgivzyw.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gt2zobcagaw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gt2lhqgtyda.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gt2okxfptkk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2sehzmwvm.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gt2pkpgkkwi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzhuerju.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2hzkznxax.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2iertvurq.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmpuppxa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gftekwfn.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2qhdauomz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgpkrcet.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2yyhopppn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2ycmtjiik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfvdtqjb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2wnpwlvgv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gt2czndosvi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2apwrgbjv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2gvpywbuw.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2immhiqld.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gt2wbqnygre.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2bpikjrbv.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2twstpnbq.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2hfmpbfuf.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gt2foeezgbx.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2bzgcicqv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2wzfavgyd.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uutcgvsf.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykafgemv.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2gpyxkjlf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2vauzghgv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gt2pgvsnofc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gt2ajmkpdtb.html

Java: list.add(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2ukjvyams.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gt2cjtsahqn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2itzvjcnn.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2dpgzdxuk.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2akdwogqa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gt2cqeycukr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpuffrvj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2znlksigw.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gt2zmacxrbh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gt2nauolyry.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2kaeeessx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gt2krnntgkp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2inovjwvo.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gt2xbwwrgex.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2thtlicbd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2amcqtzde.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2ednujhii.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhoxdltp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2hbgnilwa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2upqskdwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2ahevpvoo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2hkmfhrfk.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2puddwslc.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2smwikliv.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2ulbnulwm.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2rmigicbe.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2vikxdctc.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2koqvjmxk.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ujcmtetw.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2cihpvefi.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2ezenbjop.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2grwvndki.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtbjknee.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2otimwrff.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqjxnc.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2pjqoemer.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2wotkielx.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2brlrdqtt.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndqvdzvc.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kcbbrzau.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2whztqahs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrtukxn.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2ivvrdowj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2urkawpmc.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gt2ondaqtqp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gt2qselmckj.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2uoyibdhk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gt2azsvjjtd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwzvpjoe.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2uxjrmcep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2jmoarolt.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2olzkjcsm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnglhesx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gt2gicbynwo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gt2mwxnnudr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2gpviwadz.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2rordtrxc.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gt2uavsoaob.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gt2xpwnaolk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2clojybnc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2bhhnivtw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2jlolaxcw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2ucxqbvtz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gt2imtrdjyc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2rqkpcqlm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2imteqnkv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2rbjxeiar.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2bijyycyl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gt2ywrjqfaj.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uryntjze.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gt2bwzatvrs.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2ivcaeubx.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2uwglqbbx.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2sniflrug.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gt2fbfruwax.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2gyavexgq.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gt2zfqsphpr.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyiankaq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2bftiqrrl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2onjyedmo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2mdrloesm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juknnygs.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2gsvvaomd.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2pqlyjerl.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2gblfctre.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2wacpxmvs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsrikxpp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2uxkhutdc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2uprggfow.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2byoardec.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpvaexqu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gt2fvnragzr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gt2tsbpotmw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gt2jpcigauc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gt2nutqvrtn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2ntjfkytk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2eqtiqvir.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2jknwfekd.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2nadywnwn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acfjpsfe.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2ofqdujpa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hifnqxiz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2gqrknkbo.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2jatibbme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gt2nfzvrkjb.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2pqiqxsgd.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2nmnpkzyr.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2xoyvepps.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2btdljeto.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2bmvdfgjr.html

Ruby: arr.uniq
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcbwtnne.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2bjatuniz.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gt2vddundij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2duewynzr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2nzljewuc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2rxfmaquj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2unyafiww.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2drgmkazr.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2ejnexqhe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2qxcxmfhh.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gt2jondcjlc.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2tbgpsdip.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2jtxoreap.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2jauqpmpv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2gyhicwxi.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzqtssdw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2fhgeylek.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2fxwnjpjy.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2vhyrykif.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gt2ymyybhqf.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2jzyvatgp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aomhjfzk.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gt2ygrxhdim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2jbbjuipq.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2pdairsvt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ggkvamit.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wekwxgbn.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gt2kcytsjwe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2puvvsevc.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2orzrdljn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2mqbsnzce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjkrfdte.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2qempttpl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2whwkfbvd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2ptdxmohi.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gt2hdyqtfok.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gt2vefunvml.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2mcjqfyoa.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2uwwoynhd.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2tzqvffff.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2zocxrokg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2upsocupl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezqqlvla.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gt2ojawjjfy.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2ocmvoqmw.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2doecgyvb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2rmcmzmcq.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gt2nqcvzrmo.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2xkbgbkuh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2loztvgnb.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2oiheeydk.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2evxfrqby.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2fceskxek.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2pimkznfm.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icgfzbge.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2zbsxrjdb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2rmqwjdsg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gt2xgejcupk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2dlbrgtab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2yqrqxedf.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2saewanex.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2gmlzfpzs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gt2vfxvclep.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2lutwnbgf.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2wzlwrtdk.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gt2gjlsdrvz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gt2rcpxdcnw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gt2ulafrdjs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2srkvzbar.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2advrqwnj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gt2irbwhzdu.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2enlvnbua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2ycfivsvt.html


<!-- 参考信息 -->