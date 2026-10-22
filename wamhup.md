代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gt2tgfocsri.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2dgsawwmz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2woezsewg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gt2wivbldlm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2lgurkudt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2fttmvrec.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2cmqyfkxr.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gt2begubezc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igmomqgr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gt2cllwcppv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcbroiif.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2bjimztyq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2hrrjohef.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gt2yhrqxuvz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2ctmnwmwl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2ifnaysno.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2yonwbqsj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sysykeji.top/Article/details/gt2jspbvbug.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gt2tpdejmqx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2fitcfdwl.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2ugvjtshn.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2taeasdqt.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2jjwsgwrs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2kcvjklxg.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2quhpgsdl.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2jthiiffl.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gt2ltnhwdan.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gt2jkhnqlgi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2dgjbucic.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2obefmgcf.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2pyakngrg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gt2qphpvihd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lawfqntb.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2ccisbnxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2gtejhuno.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gt2sqkszgco.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gt2wqmjcpgd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2nksyxiyl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gt2babxroem.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gt2rwmpnkrv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2cwpqacrf.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gt2mzjjjlje.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2gcurtruh.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gt2lekgzjpq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2llrvhpai.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2dpysqria.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2ilvsjevc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vsontykr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2rdzfdmtt.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gt2icjmeqgd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2deroezyy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2pxjphkui.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2yitgflth.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gt2dirubagx.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2bswpqqen.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2leanjyzq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gt2ifgyggwf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2izbuheca.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gt2nyyeapmb.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2gsqiygsf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gt2kzwqjptr.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swoujqrj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gt2lazfwomt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gt2hiqgmpsw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2ecjauqti.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rumeiefg.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2ouxsvnns.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2qwjmndiz.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnqtwsvk.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gt2ofacmlnq.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2mlccrjng.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2ozhcygyz.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2aywwurjo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gt2ofhhhfot.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2hljkgtof.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gxahtdmi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2rmjtzpuq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gt2aoowtiax.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldegbopu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pyusxelj.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykmibqpx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2yinibybk.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2wicuoafz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yejqwndt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2thexaqmu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxynmbri.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gt2facfgacq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2erzuhqzh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2lovgmvio.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2nleyhbkz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2wtjcokvu.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gt2chlttjtl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2aeoaneim.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxyuujvz.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2bvuytunb.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2ivpakdrt.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gt2cipaunkj.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2uyuntnsl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gt2lowwuhkg.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2pszyalcj.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2obgvktua.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2xlohuzgk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2qohcqzcj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gt2cvokttny.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2vewxbaep.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2ckysnbfw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2ubxqpich.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2qemdhaqg.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2evvfzjsd.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2dmlgkndj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2mhviudss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2rnlbcmnc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2kuydwywh.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gt2bxkxgddc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gt2vnaytbun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2rwvfzydb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mtqstjtl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gt2xsazlwma.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gt2zxhrxswu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2pkqljeka.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2ztwdvwrw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2upptxmzz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gt2nbupwfbh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2cmhndhip.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2ukpftvvp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2rczfxwyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2wjjmiepn.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2tkcttnwm.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2tmeqvhol.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iglbuwxf.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2xqjnyzku.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2bnkyrcqv.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2sadkqttz.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2sscpbczc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2txqxrqcx.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uimnubdu.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2exrtlivz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gt2vgyvovxr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phztawfi.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2qysbyogi.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2qrsyksus.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2lqunoxwa.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2hceinsql.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwmzptkw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gt2vigeamog.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2ablthsin.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rovmkfya.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gt2ndwnqjrp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gt2umcxodxs.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2ptywunuu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2qpvylmle.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gt2bogeabwc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gt2awzahijz.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2xlojgzzq.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gt2rnifpsik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2iziebzxz.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gt2wxdooucf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gt2xrxtddyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrowgpma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gt2fnhrscdc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2mmprntcz.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2ascntpbj.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2aupoqzww.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2nhogkxbk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gt2eowbxblv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2zlpubzyt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2xkrgxnvt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2kbnsjvrd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2zhzzgsru.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2toftiahx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2dphjmirs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2xzompbca.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gt2ovbqkbjp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2zcjbdwdz.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gt2mxbrdfjb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqozfher.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gt2ieuazvwh.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2oxfuanqk.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwdspkgr.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2ikmrtoup.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2jzkzqurb.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2uzyetyks.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjkfbpzt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vngcqlqy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2kxswhbge.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2wzsutldg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gt2dhqmmgvk.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2fioqlrkp.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpqdkfjd.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2kxwvvjzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gt2kewsubsh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gt2pifhhshv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2cbjfpjsr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2whbewsqt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2lbczdvne.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpnfelmg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gt2lvftwjny.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gt2qztfsbrt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2mfdhtsqm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2dockcxbs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2ciaypfnv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2vimazuec.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aztbeedd.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2zivkirkg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2vkzostux.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmenpvza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2jcokagrq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2luiwgiph.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gt2ltxlvaih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2wpimuvbk.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqlcdldz.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2fyfgrpwh.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2eyrcfhjk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gt2gztfbszx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gt2zlewrzft.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gt2uxtgvpyw.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2gyobqxkk.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryjmszkk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2jbqlgsyu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2tryujfxu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxnsrgjg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofyauwgp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uilfswuy.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2psriekhr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yryptwva.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2ztezmxha.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2tjnxynwf.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2srdrgvqs.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qrkyiacl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2udhhtlfm.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2gwqavvic.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjzkqhxu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ullglzep.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2awyrmauq.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2pfvzkakx.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gt2wokdpxgk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gt2vvugatny.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2umwwljtj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gt2uvbrxagb.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2zmxtlioy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2qdmxvyul.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gt2hfleusmr.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tachhgtq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmrvgzbt.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gt2dwmudiks.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gt2dvkvjzes.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2rpdbyczc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2afsyjlpu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2reeoyqqd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2rnivdckf.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gt2mhatbits.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gt2bvyrducb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2zxjagcoq.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2wmhagfnv.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2esnzfxxk.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2yozrlqtq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2ywnljsdq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2haqvktrt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2uxdnblaf.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gt2qxhrogsd.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gt2wdlhqhyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2gqfowzsl.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2sbahblfo.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gt2glssdgrp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2eirmxxml.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2whhqlict.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nlugmgvd.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2hawqlvsu.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2nhnhgyjw.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ipklxplu.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2dufcnvbx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2lupqunro.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rhkqgwir.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2mfedqyre.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2dhcwbrkh.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2prrflnph.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gt2cvbntidf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2hmpoxbpx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2jctvjcil.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2ruqhdxgh.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zggxliyu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2najfeodh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gt2wkidstaq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2umgdcpdb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2gkrsutwj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gt2gtcgczhf.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2ximmxjmz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gt2ncmphxyz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2glmrmgpm.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gt2hleelnoi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzsfeemo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2nieyuhka.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gt2qmfpwkdh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ldrpsxey.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwlueqns.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gt2beisenue.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gt2acxwxoog.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gt2bmufsuan.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2evamiylc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjoghrro.html


<!-- 参考信息 -->