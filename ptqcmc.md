代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gt2wimotkoj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2uwzalznz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gt2digesxsu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2dqqgzkde.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ctdsfzpt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2etnrwjgq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2tbavvgmf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gt2iqiucsfy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gt2vxuwvith.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gt2ysggoewc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2tuigxtgn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2fovckoqr.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gt2lvfdbjvd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2kmjsbtmj.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2czwiyeff.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gt2cixythmx.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2zhfqebfi.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gt2elgbwttu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gt2rvkohpye.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2dcrymgme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gt2fjugzykb.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gt2ajocwjvk.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2zzlxfptb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gt2mellupql.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gt2knncuzlu.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gt2owsujjwy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2sdyzdktc.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2bncmtjbz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czlbxaie.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gt2ebbzryfj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2vkvfjaww.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2xfcbuerj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2shcnkxqd.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2xkfvkoxk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gt2vdggnjxv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2bwbmxgut.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gt2sttrtuca.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2vngjoyvt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2lommofcl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gt2rziummpf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2vkyggzvy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gt2qziclqyo.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2bawpidea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gt2csoswvxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gt2fftrwsse.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2imguanyk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2pbbbvcri.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gt2vlnxcazh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gt2shjbvwpi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gt2zshunbui.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2bymecsph.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gt2kkukwddn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2axuppaig.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2ecvluawv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhpwbpoh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2bhgvdbbw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asfaaubg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gt2nbdafrgq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdxirkja.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gt2xbgayigl.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gt2jnnzywzz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gt2ntdzpmba.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gt2fjxvpodf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yegxymuw.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2gywdtdvv.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2ylqosmtw.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2crqgohpb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2qgilkslt.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2gnfysnps.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmpxvcum.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2mhyfgvxr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gt2pziloqgh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2wjvosimt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gt2amdqbmjp.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2szyofatr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2zjzmczel.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gt2dczrxizw.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2odystonn.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mguesnuz.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcvijvcv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gt2rfrkouku.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2vnppcyaz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2exbpuhck.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gt2tcxhmxre.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygtafzph.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2udgjblia.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2djaecerb.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2gbexndmv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2gtiinpsl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2socqjsqc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gt2rluteeuq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2addmyqmo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2uknqhanq.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2tcmoskas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2qidihyoc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2zhdxuonf.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gt2kferpvrb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyhiinmp.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2wltcnluq.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2ptzabdrl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2deeifcwd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gt2skggrlmh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gt2xqxkoglr.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qndpvdmr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2esgiihxd.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gt2fivwkzmo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2dlqlqhqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gt2rvqimrfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxdnymzw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpathyyr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2esixveey.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gt2nkoezftb.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2dkeinktb.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2yqsdnnlf.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2jmnvunjp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gt2cjwaztwr.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2xtfqwgep.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2gumdoqyb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2jhmjctix.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2kffygnof.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2qobctotf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlobzawn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2hooekohb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zipqqbyi.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gt2rkxunubj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2cirlqbts.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2reqmfftp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2tlclvpkg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2ilysvjkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2behvqent.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2lnovjupc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gt2scexzbyk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2fljarhim.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxyfdtw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gt2ioditmte.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2gcclmrwe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2oknmtrhj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gt2ygzpifdm.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2iieihsll.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2svajqxtv.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2ymhfuamd.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gt2hvjdeqsv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gt2dgqlpoec.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2kxrnlnia.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2embmokzu.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2tveawnpu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2anrozayo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gt2tvpnufgv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2fkgarnwu.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbfgrgpb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2ujhxqkef.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2aibspfta.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agujfewr.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2itgvplhx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2bupcvznz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gt2aenclxzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmibfens.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2llnlqqrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2psnirobq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gt2xllxacfz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gt2hglocxze.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gt2thxhvuid.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2zzaqtree.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2cfuybypz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2vrxhtphd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2ocotsueo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gt2durxyuah.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gt2gwjqarib.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2amzvcewj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2shtahrun.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2inuipvsb.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2afgytvsz.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zrngwsox.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2pzmkepvu.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2klnmnfta.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2ggdrdshv.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2musgxwbl.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iulzjkgk.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2gzvzywrp.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gt2hodatqjf.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gt2lmlmnnen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2fywnlzhk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2obwgrahw.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2mvowiwvc.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2gkbjepql.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2tbsvjfkt.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efkptaje.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oifcknyb.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2tnoetnel.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2blvodary.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkodfnbb.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gt2yohqmhhf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2oslskwzy.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2avejnvfe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gt2jgumxdyj.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2kxcvasct.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2lmjibbcr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2njblbwpu.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gt2gnihntfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2hsvcmsxs.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2bjxsyzdf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gt2rphdxjze.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2lkvcddpj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2bnmrgweh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2odzqtgqy.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2pchhmvey.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2naozemmh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2rjbamigb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2raahvdik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2vaxwclzl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2debqrvde.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2wvzgqyrr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gt2hpjxvoqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gt2jfaninde.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2xuyceykr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gt2tmncoszz.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2eienuuco.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2swtfzvrj.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmqyzqdn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fezdpzib.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2ohtgfwyr.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gt2esanfpkw.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gt2hfbexsfp.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2fswdzvwk.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2abejkzzm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmaytho.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2totohdgl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2vaatftfw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvexpqwz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2zwmvkocb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gt2iytntdha.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2tlzgxlew.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2diyzikbq.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2kecxslvj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gt2kwgdqzit.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2ethpgcbm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2uyboqxyk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2hvdzkxfm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2fvaopwkn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2thibarhw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2iatzjfqh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcfcymf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2inoflkwq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gt2ghokjvrj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gt2gvixbbdj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2uovuojlf.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ozoawtqp.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2jkgxizmc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2jhehwbuo.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2udkudazk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2iqhcwryv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2kafcwbwq.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gt2krpmcmha.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2csukxdnk.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2wnlojtyo.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2csbnhyih.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2lgegmelq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2qluhvfyn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gt2qketxopr.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2ztgkltga.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2qgrrhiww.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gt2wzfsbica.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2ddtejyuk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2larayuyd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2owvisgkw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2fdrhhkrm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gt2sltkcfdb.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnbccwqu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayksteaz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gt2ljafgqev.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gt2bygenmfh.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ufpwhpvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2qygmuknr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gt2ulzpista.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gt2pniipqjf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2mcehllfi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2xydiicay.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2ilikovbc.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gt2qkfjrmdc.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2oeochvfe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gt2tdcqxbab.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2ghadkhzd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gt2oxrilamr.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2qefgwgcy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2nzgkqwvm.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gt2hcwzunjf.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2avxiyqse.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2iaszxrbe.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2wfaxnqbf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gt2ssezwpkb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gt2uppyxglw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2pkytxqva.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2jzgoizlo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2tjdcvpcu.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gt2vxkdmqke.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2ygszbluj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2feolplou.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2nfjvnohi.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2qaxmidoz.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2eliacjcp.html


<!-- 参考信息 -->