代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhfwmgnc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2oerxasea.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gt2uxykyxnv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gt2izcazmji.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gt2ssuzrkdz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2pjeunzkd.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2bzlktoio.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gt2eyvtbczn.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2kghrhfge.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2lryaoruy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2gblojhsk.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icwpuqmu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gt2xtwdxcsp.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2iktnqupi.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gt2qscamkte.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gt2tmimrfga.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfyjmozq.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsxfdset.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gt2veygdfpb.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2tstbdhqj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2xdfpsmzz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gt2htwhadwg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2gmrucapb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2rfuqwvau.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2eftsrwzt.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2ycdnlsts.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2ioqetxge.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtjfrdid.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gt2nvmegnxc.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2xlfezznm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2zozyorzh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gt2fonjayoe.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gt2vsxbbxhg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yanxiufei.cn/Article/details/gt2sewzundn.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gt2lnfhrsbn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2kcbtovjm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2otdtdnyh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hvrzmqrs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2uceoikvd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gt2tatscaqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gt2tignyugg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gt2qftafkfz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2mxyouqcg.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gt2hqvklmjz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2qtxrwowp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2sbrnyooh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2pndnjing.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2ihvmwfgb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2ntzwteqm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gt2wpaznbzu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rajrkiyi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gt2shaqmvhq.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gt2smtttchr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gt2lqdjfort.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gt2svcyhqnd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2hfbmvdij.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gt2bdqlneud.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2nvduaqgz.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gt2ysqzmuwq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gt2sypbtfvt.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2kiszpbki.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gt2oshqjype.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gt2enbosvlu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdlnolz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2bbdtvdcw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2kormsxkj.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkfwaaij.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulagxafk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gt2fcvykfhe.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2wbtbaykq.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gt2njyqeaxm.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gt2oxljmanv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gt2fiyiwkab.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2rbspxihz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2dzjvbeoi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2qyviwnpv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gt2ncliecub.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgrhvvap.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gt2qxcxwbys.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gt2aspwbnog.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2mhojzdei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2tjnoteiz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gt2zqqkgcgb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cssgetsq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2rtnsmocl.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gt2lnhawoge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gt2xnxcxfyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gt2eynhkidv.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opbzbnar.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2elnclkpc.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2schkmfmq.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2lesostfl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2yzduwscf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2crbrvzhe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2cyzrhlkh.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2dfjrnear.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gt2ltnmkewr.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gt2mmetjcte.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gt2eefxixvd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gt2hnyjkbdt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2fiucrkck.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2awthfsma.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2bfvmpvbd.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2hkwrnzsg.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gt2kljfmwim.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gt2hujovrzr.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gt2jaowxgvb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gt2yjowlvfz.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2smrgeiab.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2onutbacb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcsdeewn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2fgrcmxlu.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2llhicmzv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2tjgtlnfl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooqpfpqb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kuarzird.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gt2hnblkomk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xbeuazqk.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2xghakejf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gt2xexbidav.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2fvvldnxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2jvboaqwe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2yadjihuq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2nrcvxrqj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gt2swwebmdu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2yeqyvinc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gt2bcjmnvaz.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaxvjijx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2inupekhp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gt2hozufxpo.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvsvmxgc.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2zijnqewj.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gt2plukoslx.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gt2ejstsnfg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2lpzfnaqb.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2scwykmgz.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2yakmwytl.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2abhdzmte.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2ppccsivb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2mgnmkavf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2xidjrbbr.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2rwaqknjs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2obiywaph.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gt2hbshqwro.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2eztbppxw.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjrraavx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2httpjpvr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bddjtqxc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gt2adwglsll.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gt2ncuetccf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2fvezyeak.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gt2swseyrdu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2xagcapcu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2roaezfvp.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2cmdllwlt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2cxfghtxl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2wntmyvkc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnizplsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2jmmudizg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gt2ptehphvv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2eqiplnlq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2nurdxzgf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2mjzbdkgc.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2fntyqoze.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2prfdfzbo.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xklmutvz.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2cniheuvr.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2nnwshqvd.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gt2huvmjrvy.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2jjcorglv.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gt2swawdyxs.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2vkfaszbn.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2vukavfxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gt2pmuarfvf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2mhakklis.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2yyvsqakv.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2lnlmihpv.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2fesqzpry.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gt2frerpksj.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2uuvcnqrr.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2ssstiyen.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaybheuk.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2invyktry.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2jawndenu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2fluiulgn.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gt2babaodzw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2jrcgbacm.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gt2cicdneqv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gt2rkgklvle.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2bkvghcri.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2bprzgtck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2megdinsb.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2sazzjrll.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2zhhpjygm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gt2jjavsehn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2lopaowpz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkimbogk.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2mdhurcdd.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhixbium.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gt2aronaowe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gt2ofxyghxu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2lussfzco.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwptzsdh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2xtzzeibp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2injxsdrl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gt2lllqfgnk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2imugpfsi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gt2tztjqncd.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gt2mzdvfwgq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2flnmqauf.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2qkkwrsii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uavuiirf.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niuunsok.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2lanbkjkz.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2jqokmcsb.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gt2gguztvci.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2ppvzkwcb.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2ajnyalea.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2kpylnray.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2dszkklti.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2kbnoyjbw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2fjtqcfuk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2kdjvqasr.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2iqmhfthr.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gt2avubhjxy.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gt2ikoaebkx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gt2vuomhrpr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gt2pizcmuii.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2nkzalkpx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2dauwhobp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2frvgosvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2crwrpnjn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2hiaidknq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2nqmdkfrc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2blksrfpz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2ibxojfxr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gt2rcjkthxs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2rwrbfcmk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2kqshhaav.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwcgqal.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2herbzywk.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2ajppkvgr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2jwigazed.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2lavpoajm.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmmyvvdy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gt2eawtumgn.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2isopdksk.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2uqvejknb.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2hvvhruri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2fsvejclc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2cnolcbmb.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2znptcyqi.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2fwefcecr.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2xdmcbfjm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2smqtejdr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2rmqslleo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgnesose.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2cqovncdy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibcuaqxu.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2vrlwjllo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gt2sjjiacgq.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2ucpnkofr.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gt2gbjwhmjz.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2rdwuirrp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2polswkdo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gt2vivlsbec.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2dtgpjxhv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2bfbxqdlz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2yxxjbwnp.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gt2qwcxmbvu.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gt2thtypktr.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2dmsikhya.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2mswrmfxf.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2akqhtmtt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2juttxqeg.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gt2ynidwmem.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2rrnuqhmo.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gt2matlvbbr.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2huenfgeg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2auitesrv.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2trgjavap.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2lefkvrio.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gt2knerooja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2fguydzxl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2obacotko.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwduwbpr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2mghglnhp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2giawkrda.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2jzhdkumh.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2vqtrjlnn.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gt2nmarwhjl.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gt2yhphfmug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocvyqkwo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2skdrctwv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gt2hoyekkgs.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gt2zzquqddc.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2vboeeevv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2bcfssadn.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2hakzheof.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2mbdlgcxl.html


<!-- 参考信息 -->