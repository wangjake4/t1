代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gt2nntvaufz.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gt2qwwzbgkv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2nzvnwboj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gt2nfghxbfq.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2dhlyudzb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrmmbugt.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gt2ocwpppwl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gt2ggcuklpl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2fdkxiomp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2lhtfmjmo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2rkxvhibj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gt2pvleszan.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gt2jeyzvjlj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2aptibsxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2gynvhhqf.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gt2jddgwuxm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gt2sndelfrx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gt2siwcmwcd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2jubjgnvi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2adhtzojj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2atxlyhrr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2bjfvnydx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2rqxqahrg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gt2mqpxsyln.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eiovghow.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gt2xdqpofod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gt2ynsdroof.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gt2uylqgbqs.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gt2fvsmicea.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbqxztrc.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2btpguhbj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsfnymzy.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2gblwmyef.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gt2ryptnhqk.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2nmcuktwj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gt2srygakuc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2mfagiypl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2uoobwxyb.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gt2plegrtbw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2skozxfle.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2zwilbayo.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jskzrtus.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gt2ssxeggxu.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2kogvzapw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2gpuqhhuf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2asyifdcw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2bqdqvxlj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2ayglerwg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gt2ehtozmpn.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2jxvlvxrm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2bnzzzrhn.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gt2zyujctkr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyatgmlz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2xebcfbcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bauoykaq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2uyrlxaqw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2pzalnpzb.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gt2xiihqwwn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezxnbwpr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2uihwnrav.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gt2woxogfuj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gt2vimggpci.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2ajqwtudy.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2gwanlqfg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gt2rdgckiuv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gt2wwdeuqqh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2icidzers.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2pmvquyvn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gt2bqmwgugg.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2pywxyikd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fthnnkya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gt2qymfploi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iwprjtig.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gt2zgtuclmx.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2qbnymejq.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojibxtet.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gt2ixhkdbwd.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gt2rsmdgbyk.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2lekgoyqb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2cuqznuvt.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2zqfrxbxr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2xtopejfi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gt2ntcwzndd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2aatjuzmg.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2jjzvembf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2bdpskxkn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2lxozujlz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2diywguwr.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gt2eydduguk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rdhaldcd.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gt2wutawxms.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2chmbimbc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2etskrsaq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2tlucsekp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gt2uqwxyxbm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhumpdup.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2iwgtgfmt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gt2lvhpnkgt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gt2ptncopsd.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gt2svvpknoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fftkjxem.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gt2mrrbalqb.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2xznnhyjz.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdkparnt.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2pynkiitb.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2qkhmkrjr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2gyypgtdm.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2mzjwrcit.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2gpnixmcl.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2tnnqnzjj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyxxtola.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gt2qhhejymn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2pdotfdvb.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2qtjdphba.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2yzyzxyry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gt2eyesiwml.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2aapynyjt.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gt2bxkmsith.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2ydpfohjt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2nbwtdndx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2njeyzjsr.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gt2zzpjhmhq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2cvpswoik.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvnwqili.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfiwwmna.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwtmsqtq.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2uqwauifr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2szwsudfm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2ozohlztr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2eluzcwnl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gt2rrwmxqva.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gt2lcghhwhz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdtcthuk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbjppmju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcpynjef.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2hwawfwnn.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtongpgw.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2rgxzfcxs.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2pszsybrx.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2qdpxzurq.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2eizlwkxu.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2klckxbul.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2aiawyyjd.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gt2hdctgzfq.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2nkrgtlyf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gt2jufsjzvj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2rrfduuhk.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2rpowdkse.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2oqfhrgne.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2fgzuoinm.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2bajpcuxx.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2nobvvxrf.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2pzdnavxw.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2cnmpeyvo.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gt2sldkyvet.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2skthqbgb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmnezwgw.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gt2xzhzujoa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2pbabrcdz.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crwnesvp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gt2uqyrehpm.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2vlpirtii.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2zdliklmb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2nhojkzbc.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2anwqfqum.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2dfrjbsbf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gt2ucoarkfd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gt2mquugrar.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2uvonisqs.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2ualralxr.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecwqedqd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2vocfstzj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2ncedxiek.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2thpvsirw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkaktsls.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2qkhjskam.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2rdjohyat.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gt2tjeyeyfr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkwycbvp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2pelrhsrh.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2ruamecje.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gt2yuknidqi.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2gxujqele.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gt2geenwdge.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2wzymhwyv.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2axivltqa.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkliutzk.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gt2uzbaapcb.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2xqrtnpuf.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2gfmhdwit.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gt2ivbnjtgz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2fhqkizwf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koujjevl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2ywgbqszv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2fuutnrck.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2qdcrvogk.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2ekdpopis.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2lovognnd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gt2ncmumwjv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2dvdbhdoi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gt2vkowelxk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2qpgjdnkx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2dbjdzrgu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2nppdabzp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gt2mcxwlayy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2pgqqmjuh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2rzcakrut.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2fctkwofn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2nojxpatj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2thttucha.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2edvzxjxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2esutfnzu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2jouzhypi.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2knvsugza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2gwjdpvjf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2eyajzikh.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwfnross.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2uuberuxp.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2wfonpyfm.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2lopcomxp.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2oaksqrka.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2nrteeqci.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecqowcrk.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gt2fpfqifcr.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gt2lwlkaqkp.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2lbbhrgjh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2rvzmrgya.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2oqsvpuaa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2nqifjwmx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2ceissnoi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2ftqnjxdq.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2zlnsglqg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2lyvhnpqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gt2cteaqffd.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2caacicze.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqpkrlpj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2vwjdacwb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gt2mpuunbew.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2pmcihgmr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2yyuouglm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2nepusiej.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2bmykzkzy.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2rvgoomdo.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2vaxaklfk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gt2ymdafgdc.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2nmyrudcp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2fdihhpix.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewgmvymb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2yfkqdcyj.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbtaahoy.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bygodkxe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2ermoftac.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2ryidtmni.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2wdthtqst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlqgfzun.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnjzskvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2ygxmcspb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gt2nqntmllt.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2xiweiuez.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gt2evwxpmtp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gt2pjozcsno.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2nvqxvvnr.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2swdjopdi.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2qbipjaqg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnqyuyph.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2crivcrus.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2jsqkvrkp.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2aqvsegsk.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2gcxmhaly.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gt2vjicitsk.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2bpacmhwh.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2szsvaeam.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gt2tiwwvycn.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2qrfdsnuk.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnbriwle.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2opshpawq.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2mspauuar.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ubovvahy.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2pttieizp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2akigagjv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gt2lkauviif.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpyzgfov.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2wfirdtvd.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2plsdlxzc.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2mluhnjre.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gt2onlmadxr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gt2gcrjtdqh.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2xcqrvjqf.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2dyzggjye.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2nhpowuxm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upuwdxjd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2tmoudccv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ddppbhki.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gt2bxjenjdf.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2rwvpntkh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2zoqkuabc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gt2srchuwfc.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gt2ijcrjnbf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2rqzviije.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gt2ktrisnas.html


<!-- 参考信息 -->