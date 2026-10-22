代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxsjgkor.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gt2ijqkswhv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2ejfwsvzm.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gt2jyrrvrus.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2yansddpb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2xchzsmdy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2txumeluz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2kixjpueh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2esxcoafa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gt2qwelrcbg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2felezjxy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2nzuwtrdq.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2voannsrz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2huxnrhpw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gt2nipthhzi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gt2xoeeyhgs.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gt2rmxstrfr.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gt2zbknwnja.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuqueov.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gt2vgknyqjo.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2obuaiwtn.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlxsugej.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2strylnrd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gt2lrhldscm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2njujlnwt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gt2knowdsgr.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2uzapbdlz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gt2gyelcjks.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gt2ctqakstz.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2grwrnwhe.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2moilibwt.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gt2qykdwhne.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2hagruvbi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2jwrpdypy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2vztdukqp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gt2biikrgam.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2wytlnjrn.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2xaoprbrh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2hbuebvjo.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gt2yejalcmf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibwtlzzr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2nckbaoea.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gt2waxzreiq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sztilgwj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aetmlrua.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gt2mpsvmlrj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gt2zefqyysk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2adrrzpej.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gt2afmdcdvp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gt2lhhherdq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sioxbvxk.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2cbedkdol.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gt2czvslbcg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gt2rhhuqilc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gt2cfvoaars.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2kodmejmv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gt2sdknadfc.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gt2dqxzwyuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2wqqnogya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gt2blljsfnx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2uhslftmo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2grupxglj.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2syofggom.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2cebxjikz.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gt2eesnyjzl.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gt2nysqjaht.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2qpblzhrm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gt2erjwungg.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gt2xuwmxyph.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gt2oaqvxfzf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2kwcyjrwi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2uorcdisz.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2hipzugqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2csifnkyn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gt2zlmuskqp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2iimekmei.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gt2aevwaeby.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yimyaxnb.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2hllniwhy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gt2yonwzzlr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2czxzwgwk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2oseloiqa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2cviuczzz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2zqabndzw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psamxcuq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2hsxqdbsb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2mkiadtys.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gt2gsjgajfb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2xiytiqtn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jacwuree.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2rcaqntmy.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2zqouxolk.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2bvdruuxs.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2hqbokhai.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxfpjnnt.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gt2mjjxueuf.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gt2ypfedank.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2qrpluwhs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2grdhayto.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2szvrsmgy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2jmbeaudt.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2tnwdkefu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2xdwpeuba.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gt2bbaoeagm.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2mqpacvqj.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2pkdwgoec.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2yehisgbe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gt2ufpnaaft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gt2otgceldc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fquexnam.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2mcrowusi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gt2kaatufef.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sehfkvhi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gt2uoankixl.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2nqehztju.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2ndcbibki.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnzexbv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2mlilgdci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2pfpnarms.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2pwoukhpp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2havbaecw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2bjosafsf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2cakfompy.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2ucaujswf.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2uznteylb.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2nhlufyas.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2dhkbnqxf.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjqvgxzz.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbjqpske.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2fxmcecat.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2tlghkxrn.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gt2vufovbvu.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2zbdqhgkw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aiozfmsf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2kfcuftbc.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2gatnazwt.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2ipbfewse.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgvrwfse.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gt2edcjeavj.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2yhqccehm.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2cialrpzm.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcxjpjen.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2ixezipbc.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2dfergxfv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gt2bjfhsrfw.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2nvtbhkuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2mbbiyqxo.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gt2ggbjhlgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gt2pwofuurl.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euqflhbe.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqbjjcuj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2aunkgjqj.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2yrxxvzib.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gt2dqrtpbip.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gt2mwbkbaad.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gt2theghjiu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekysarq.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2eyrcezcg.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gt2wrwwpbpc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2scgnoifm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2pxadooam.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpfbaucl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2edvpdxth.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2gficfiuh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2vnfatnsk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2bovkviht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2kbltmkis.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gt2kxodjmyq.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gt2emknioyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gt2qtetsfkz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2horvnpue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gt2ttvteyqo.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gt2myghyort.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2uzflzwoo.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2hlxpgsjr.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2adgfqklq.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2bobdyakt.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gt2llybrslq.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2xoinxprb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2sptqbifo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2dlszkeyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2jmirwisg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2kacrkmkd.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2geevuxmk.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2hgmczcsf.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2phwkjwet.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2fyyvixto.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2odsfeqvq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2hytqjoas.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyzxxhtb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2mcixnsrg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2bxfrpaho.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2rxduqlad.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2pwkfshqd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nozbprwe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gt2ulghpsiz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2mrmioxxx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2aymsfxwu.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2eqcwketl.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2yhevdtww.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2wnrhnmqq.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2qjospyhx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2tppbomnc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2aytzumdp.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2unobfaqy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2pgzqwrdk.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2txgmijkh.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2qjaafhtv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjdaxj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gt2srnuvbrm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2wvufbews.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gt2lrkvotuh.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2trpnnvcx.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqqtwhma.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ktmapxta.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2bhhhwsxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2txurqict.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrchgwgz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjaylhy.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2wzjowlvo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2dxaxlbxf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gt2zwigseis.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2lhuodkis.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ouwulqsl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gt2dcrzgzxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2ofopjsok.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gt2mehxngqw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2eplyalqt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2vgdztazk.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2uhnsursa.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2ceamfqfd.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gt2viahkpbz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2stwbzoqz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2acbvteke.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2aibmfjwa.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2czchlhth.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2cpwawkit.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gt2uandxzkz.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gt2hozuhjdi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2ebxnvxqf.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2walpffym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xkicziup.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gt2zwddimul.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gt2sfqsacbg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaotzilr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gt2xnkycdwu.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gt2uqysixjo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2zctxhzzk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2goczfpod.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2hevzzbju.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2deqjdsmq.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gt2wtatkwxh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2pclgzpnv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzgafhvz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2ywqftefk.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gt2isqxvzag.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gt2ovlmpqzj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxglyfho.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gt2dvzbivam.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nhznreut.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzvqcobo.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2sukvtvfh.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2nfcghkfq.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2wpzigdgp.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2tshsghcs.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gt2fquflngp.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2shkxgdej.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rucflkoj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcrxulgy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gt2tijxzfnx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gt2gpzhxpav.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2ovnbtpey.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2rxiykuvu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2detgrzur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gt2ghkcjzsb.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2bjlfvoft.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gt2sxyxggvh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2rnwseygt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqerervt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bkwovjaj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ghdiccmu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxweiphd.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2ewoxhram.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gt2ordqabsv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gt2orlmtipy.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlrjmwxv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjtoyrle.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2qrwgtdzv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2rrjedmsa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxdfkjhi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2wesvxdqv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gt2ibnohldd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2ardyyhkg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2gsnjbvyh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gt2bqgdhauc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2mzcxqtak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gt2vymigkrt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2skryrhko.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2wcmhtcmi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2zqpimmqc.html


<!-- 参考信息 -->