代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtdyrxnpbv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtectnfhya.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtxkiyavjq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtmvchiiav.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtimmpgnqy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtdgomrhmh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtmnffvzhc.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtkbkzfaam.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwybdyiny.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtgfjbjlom.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtjhqgjbin.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtbpzbhboc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrnjpcbdi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtxjzbdfsy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtmsxtsjma.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtboylsjgk.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtisboghtm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtkhhpbsuq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtvyqexlqu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtdabqgwxc.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtchcxgiqc.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtnpsoklcc.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtdcbcepao.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtbisugecy.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtelnbxlcs.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtcuzrwqjd.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtccvrltrh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqduoifrt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtnuxmxhwj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gtquhcsros.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiztqwrzw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtclgmqpet.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gttarrihxj.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtlknvzmpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtreojhyus.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtoqycmcqj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtuvxaeyka.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtlwlapqoz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtfqvyzwtv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtcmatsaos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtfewddxck.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtmjrxcgkr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtshqhplhl.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtkkegkmpt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtexpfgvfe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtqecnapfs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtwevrrqis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtgdmfztzc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtyhvyxpiy.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtishtgkjd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtmkngqxcw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtyotpbzhf.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtoddcgghf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlhkrseu.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtzottaabq.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtgqmpehfh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtixtrxkpn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtgubhgztf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtszkpjqup.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtdofrwgjd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtorumtvpa.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtdkbcfaxb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtqyoioaff.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gteezyjghe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtttlrgmvt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtbppyaixe.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtsewgbfxy.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtwfbkkbyk.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtxyhdbhzb.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gtbggkbrsl.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtlbpvvrer.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtaahdvvif.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtrnjwojyh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtiwwjvvvp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgmgynnm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gthwztctbg.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtjhhdsulv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtpllxxsmy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtrkllgcrh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiwlxaflk.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtafmyuujx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtljnwplyr.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtbskldelj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtfhqqztzp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gthczbclls.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gtcesfbtey.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtzkeqxhiq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtngaebnnc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtxeylizue.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvqulqpj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtypcwhpeo.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcxwazxh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtypsogiov.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygepchjt.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtpodiqwql.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtbtnwzjfv.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtyrpjxhgm.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtpaxynayj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxwydiiy.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjeiasvi.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtgymdukvm.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtewafadbo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtocfmdown.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtnqupxnef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtywubeuee.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtjjzsslxl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtjimjuaoa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtculergfq.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbywrjpf.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtjpyclvtw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtvdmjhlry.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gttchkalqt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtrqqaccre.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtbqjjapcb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtfibovakw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gtjfcqmcec.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzqwljpi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gttmhmdyim.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtilskyvhu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gttwipfyun.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtemgujidm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtzkjsdaro.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtjsvyndqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtrrurzyxq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gteabhiaik.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtvxzdapmf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtpfprydso.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtomfqsuef.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtesqyvheb.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtaufjfiqb.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvenbbzly.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtcezvtsou.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtmajctmas.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdugshenk.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtnjchiwqt.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gticgglvgw.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtrhvzqxan.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtuzxnrpyw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtpncaskpp.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtktwjjhmb.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtsygizmkd.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtlslisfcu.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtbsszxcca.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtyvviqzgv.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtxmcgcgtp.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gtyfgiyywe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjavjpwod.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gthtfyzknt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtodrgriuk.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtxnxzjdtb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtnlproafl.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtfmpkrwhu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtrbwfxnbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtqnibnslk.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtlmbdgqyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gthrunlvdg.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtfebhjqse.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtwoilqwzl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtikmjnpox.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtvodaodmc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gthcbrkdlj.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtkesskbsx.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtavbpcrmu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtexresnud.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtqqghtfcw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gttipduimg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtoiohuflk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtmbcawrix.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtgsdvmbzw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtgwtsywkl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqgywyfg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtiyzxyksf.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtehpubvlg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtzpmnddsp.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtfdladasn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtkrbtmtap.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbhglequ.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtjmdzsoah.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthnfzwmmc.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtvtjqlnfx.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtprdrwcjy.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtyoxjkmkm.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gthhbwrfdg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gthnrhhfvx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtutehrqtc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtftzkukgq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gtogbockro.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbkaotbox.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtfejfllwb.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtydrkgpiz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtjlhwvddq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtiyvolxqf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtrynbotli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtiqopvjoo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmrlrcmh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakmjfrvj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtnflrdcdj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtgrarfkqa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtyljofwwe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gtqgprbexz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtlbtounwx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtvstcsyfs.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtuacoubsn.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtqpnvwbsm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtesfakkqf.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtenpyaluz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtyyhnostf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrdzjjua.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtgudruwul.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtctzhspbe.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtfwpbtwwv.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrgwqiaed.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtzdiuquok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtjcdysszz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtulwiehuk.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtexiyptiq.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gttbdxkcpl.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtdfvqsjkz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtreasjpen.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpvfpjrmg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtffhqihcc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtfufbhmkq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtpmshqnmf.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtwdkntnjd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtfftbunln.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtmvupfovt.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtrvzryvzc.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gttqgkpdzv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gttapjosoq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gthteyzviz.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtsfcgjruh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtbcirfqve.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrmkxikwy.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtuuxaywzf.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtmrobsujm.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtwbzvgler.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtgsjkkqln.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrksunzbi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtddvdygjh.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtiezsaubw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtkzauhbva.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtgclpvsaz.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtirssrmiq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvfzuaprj.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtcnybapyh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gttmhpsmti.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtqkeytkju.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnqyypbd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtxferdtdl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtaaldurnj.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtqlbenllk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtvxfuiwhk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtzhkbpuha.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtpbtvrpfr.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtlrpevdiw.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqzoxpzzf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtyhzwlnmo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtdcrsjmnb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtjbfimjpv.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtdisegick.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtmlcvnmvv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtsdmucrnr.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gteuhsbssf.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gteauepyaq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtvcetxvov.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtlvodrwey.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtezckbeuq.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtgkcjprxu.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkbltlzl.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiocdbsrt.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtfxcfsxyu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtyjzwqixn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtiiuoyiod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtajrywnez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtdywvbvzi.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtxcwepyrb.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtckighbkk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gthidgfsxr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtyaajrwau.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtyqkdiiik.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtrfxlopti.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtpppjwont.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtqlmvspbr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtemrgsbbr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtvwxxpdfh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtwfxjzrtz.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtbbqmvcji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtczniceai.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtbqyaifdt.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtjgchxlpx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gtpmfilhzj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtbqchwxkn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gterbvusdd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtuejlvkjb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gteirpmhpd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtelbhsjwc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtvtflciwe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtieexwpug.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtfdzflsqn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtqnmkgnwz.html


<!-- 参考信息 -->