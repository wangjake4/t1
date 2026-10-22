代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gt2ikgnrckv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vraysdkl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruveeqnk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2avyfygij.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gt2kxidaygq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gt2uxnvtrdl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2doobdqnh.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcpxrgvb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2jsmdboaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2audarmps.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2ixlbqwuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2pxqssvan.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2ltwfnryt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gt2dlcmtyph.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2asowfjis.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gt2cvpztltd.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gt2ikpqtlny.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gt2ofgtrran.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2dnynfgxa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2bcunrqih.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2azwapjzj.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2nwdlmiki.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2hjevlvjd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gt2txgscizb.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2pyjpzwls.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gt2udmrvwfa.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gt2kkdiegcg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2bfoznvcv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2tpkkmpzj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2rbuxxhme.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvvrisab.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2sfmoqkva.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2lewaplli.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2lcpyksed.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpskfugh.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gt2idsmqtpe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gt2ximvjrws.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2dfgiuvgw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2ayzoebjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gt2sycbyyfb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gt2golsgmli.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gt2intcqxhz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2zebtoncb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2nceepuki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gt2ptlzysoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2petdxkmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gt2xzrvpfxn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2demwdbyx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2hbdzavga.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gt2tfmpwgou.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2ehkfujxp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2mqmrvaet.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gt2thngivvu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2llfyxepd.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngmvvicg.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2lwwsphkc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2mfyfjwbf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gt2ylaysfje.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gt2egnhuvtt.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2kzpqthnn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2kgxovejq.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbmkleoj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2mcvmcxau.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2pyyvwxln.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlsmupfw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2wuzxngfl.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2cmvzlvys.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2loxyoxiz.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2mvprbgdt.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjbqjzlu.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2vkhrqcuu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2lmaozliq.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2xrzzxzst.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2bveyshcm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2rdlumvvp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2axakpmvi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2rgybsleb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2wcdotegw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2svxpcrqd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2azkmsrho.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gt2bbsorcut.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2infyopag.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2afiihqds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gt2avnaecgo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntxtlgpt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2ilgfbzzd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2ujzthqta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gt2gnjcnozg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uspqqooo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2numvugia.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gt2mcwoxltb.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gt2nmbxdllc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkkakuez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2ajmooltq.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnmdljna.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2lwhfgjsn.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gt2esasakgs.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2mgjqossz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gt2pcdiuuwc.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2xurnnrdb.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gt2gmgatxxq.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2vgxiqgqf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vowcrogl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2nnigacxp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2fmteodkf.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufujdhue.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2bdhyliud.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gt2kkbvgtpp.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2uguomgeb.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gt2hotupoau.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2trydcbhn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gt2kaqtrsqh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gt2oqxqlxzs.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbcfsthb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2ucmdrvvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpgsngln.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwidxvpu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2yafhdxha.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2qewkfwnk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxrwqazm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2deghtlze.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2aydcmhyp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljqnhjbd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2aiswuvmb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2rknjudcl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2wfmrfwlx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkbdpxxk.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2vyqvmhlf.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2jauzlcwj.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2fxkdbkmw.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2gngjeezm.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2iabbeqkx.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2xedicijz.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2oclryoha.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2bumfqknh.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gt2vhkwvbuu.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2hlcllojt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gt2sbksggga.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uootvmqs.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2sskxpqyl.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2ijbypfdp.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2qtkvpdyp.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gt2oarxhvjz.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2hwkkkdch.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2cgwjcclr.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2tkildqob.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2vcsxjogl.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gt2dpmmetop.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2bneaqznw.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wluxfpbi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gt2elcrjgxk.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gt2uvafcpxo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2haezpqou.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2wbgpejvo.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gt2grkiddvt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2byvtwzco.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvjpezxf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gt2zpojyzlc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gt2fklzhxmv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gt2vjjgevue.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2ycfscprz.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2umnobeyf.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2uxbxwjwx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2iklkcpow.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gt2ogitciin.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2hpsepfck.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2cxptxwkg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2nmzmhoda.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gt2bzcfroqk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2ivxwxvrd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2gwggpcjg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2dvtfcicq.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gt2zsdqvscv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gt2kookqjri.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gt2aigjtyqr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2yyjzztod.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2tfnpmose.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gt2zytxgwtl.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2nklieari.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2zuxmjsad.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaurllis.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gt2kfnnseyl.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2fdfvlbqy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2krpjjpgb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soqcawhg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2hppbgiuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gt2nymdpujf.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxinagvg.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnhaozqu.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2zjxrhtfa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2midjpekq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrdvgemj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gt2knlmvjnv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2jxenrehn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ttdiaevs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2gdxccmai.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2whawhpux.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2azkqsgny.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2qcjntosp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gt2zsyezlvf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gt2yqlfpnri.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2uiogvwoj.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2qnqzppty.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2optnzypu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gt2mqcfvjhi.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2glviywnh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2rwtcogxn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2uebjdpdk.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2qyujaklu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2ltsbjtdp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdiutzk.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2uhwxhats.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2acadixae.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gt2nkhxezxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2zfzibrjh.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gt2osaikoft.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gt2fblcdeyu.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gt2pulrydcq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2wowkwqvq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2zywjldfi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2fsplfber.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2vjjjruhs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2xrrvamyo.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tikxhkgp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luupbnly.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gt2fbgxiuft.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2vtfbcupg.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2qllxupaz.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gt2mmxxbxxy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gt2crgpageh.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gt2xwskhpat.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2jeiifnkx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ynkrpxtq.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmnxamox.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2qavdkuxz.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gt2hrztycfe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2diadbnpy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2jdbeqedl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2fawguuge.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhwsnegh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2mhkmwzej.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gt2rvmwhvjp.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gt2hfierfxe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2lpfcwbjz.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2toypyygr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2gmqrtggn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2flaescna.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2ltjbtzql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2hfwqirpb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2cwyxlebt.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gt2ovbcuxtp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2pgirytru.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gt2ikpzbjno.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hghfwimp.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2bbeqghvn.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ybbuufwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2okwvlyjr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2twxhpgmw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2asrqullw.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2jeldcfgo.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2aasoljmr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2vukdarkq.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gt2ejqjofle.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2viprnuyx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gt2uuwmayst.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2gqmguqpn.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wyybibeh.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2vmvjuzne.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2pydfdkdn.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2agwdcehh.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2xdxetmph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2jlohrswd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwiwddls.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2iyrgzpvf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2pdtskvcr.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2zhhsmqhk.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2asjjpfpg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2xgnomhgx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2kebeqauz.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2toyovvxe.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gt2qiogchyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gt2yntkvaou.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2weleyqni.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ibdwxizp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2zlupizku.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2fjouldfw.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2tkztlxeh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2ajaybbuj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gflwxiol.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gt2uonzzmnh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gt2dxzndvnc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2ntulsbbs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2cghnsaly.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2ezwokiln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2qulzkpal.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbufeflf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2xxapaqwx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rflhgeog.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2zytfffwr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gt2goxeelbe.html


<!-- 参考信息 -->