代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gt2ncbjpxlr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2dwepnwsf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2egfvwfhi.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gt2xycsavve.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2bkuwebrp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2cdpkszfr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2jkbvmrrt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2ccgidgnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2nslkmibq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gt2mmsrxeyk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2ogrbhhel.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2lsvugpem.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ifqinqna.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gt2hwmhdmlv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gt2ovmuhvjz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gt2xwmhdzij.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2wrrqmzdx.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2mgkjhqvp.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2vzcjyeth.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2fwuahaiq.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2vddtfvzs.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2antbzrwt.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gt2irkmobyz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gt2unqbjzna.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2horpqkfv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2fdcwctfh.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gt2rvwjquaz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gt2fnqftqwf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gt2ygrugjdo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxevept.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gt2yyctyddz.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2ppzdljlo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2zfljqigq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2fcpcdfuo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2qrjkwtdd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2niciwsrx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gt2ovujeouu.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gt2fngdibkw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2kuwnnpff.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2ynfpetkz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hntgpbto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ifxualmh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2okstzjxu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2nlujjghx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2shlkkueb.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cviwrqkz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2cvfiwlse.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gt2xrbpiyhr.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gt2ljlhqzwl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2hrtfhcqb.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2tljfbeeo.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2uusiubid.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gt2rotdvnpr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2nmhsjvod.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2vmycsmdq.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2wkznvrvk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gt2dhswstjh.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gt2tychxuxs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gt2rnnfibyv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2lmknmeaf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2iwfmdccw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ploeerjl.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2zqfibfcs.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gt2cokahevg.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gt2qxxrykpo.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2mqqqduqr.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkldqyvr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2uzczbufu.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2cohoyero.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2pqvndbhy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gt2idluudxj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gt2iylpikic.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2utvkrmiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gt2huxcyqxt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2nlyyvkbt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2hvsbbyrc.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gt2hyvruqpi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bcebyycc.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2pevabitg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gt2hzehnyhg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2nkfhvbbk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2tvixzivu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gt2lnijeroe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gt2yznpamui.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2lagkmuqi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2uijfnupg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2tvmxkhzz.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvzurhiw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2xmqnfynb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2xywofolx.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkvwuqdt.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzukirjy.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2reqbjxge.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2qctazrmv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfniegbc.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gt2gwbizwwi.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gt2lawzlxpt.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2cfpjvobm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhqecxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2gourzgph.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2dvmxihae.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2wbvdcpwd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gt2slyiqhcz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pikbctvx.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2utckqpgy.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvkwwgrq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gt2drhdltsw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhggcmwo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spzcncxa.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2ssheimkk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gt2chukbwfb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcqqmisa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gt2gbpadqls.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwfedxga.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2qygjagbq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2giciidxi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bowtecll.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2wxlptzqj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gt2lycopijb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gt2zzfhgwzm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2oowhzuaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2wdslubcu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmsvpsgi.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2uzsblcoq.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvhepsip.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxhmzopv.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2foklrycj.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2xvrtgxwa.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2pcnlflqu.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2cfrfosor.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2fccckjxt.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gt2zqywsdqk.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gt2lcevdoyz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2oghmyteb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2pyvptmtp.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2tjlcbwej.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2bvomrlgo.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2jeyjnvnp.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2qvckmtsk.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2ntqnpzbm.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2qqsauncl.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2fenrgfvd.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqijhwea.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2wunculkc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2uzooapac.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gt2zqltgfpz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2ubhyabdl.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2tedbmcyl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2pylsmcyk.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2ijosyyyi.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gt2nihiunca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2aboqebhm.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gt2eebnonux.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2tbsjhlrv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2adrumcgo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2eqbritxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmpmrzop.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2ggtnrwwq.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2tjzhybok.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2ogirwiqg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gt2dfpvbhog.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gt2ahdvnsbo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2zviazpvn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2sedijpis.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2yjtlxidl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2kaoojpwp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gt2hydcutiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gt2ktphomqx.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2qoxcaoqm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlxmvzax.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gziudtyg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2hxvgbyre.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2qdsmuzjz.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2umlsmbix.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gt2qopasrgm.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2hqlcocnw.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2zoltbjba.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2oekmmyjn.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2bcxxxqug.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2offvsuiq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gt2olowyfkz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2onocttul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gt2zbgffeic.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ywrooiok.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2obecqovc.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gt2pzjsizun.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2ukmljqgf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwzdhbjf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2yyxpfjbe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2hopencaz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2qyjraetg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2hupmvhdm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2plpgrksd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2dbonrfee.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gt2sinbzvfq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2jhtnaxfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2dyfrvstp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2bqdzufqs.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqcendjz.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zntqxthh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gt2zukpruvu.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2eozaxgew.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2iuijkdfw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2tjewemce.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2imrswxvl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2mlowssey.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luzdkfvx.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2trpikamz.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2roqftade.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2ydinyvxg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxgoubsx.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gt2dbekaxva.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gt2vzotargr.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2txcavank.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2rgpdwmdh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyuxpmtd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2hflsjgra.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qgahxdrp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gt2fapczndx.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gt2jkxregqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2ixhnlkch.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2tpfjidwt.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gt2gfjlvzno.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aaymqlbc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gt2xuwecnqk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2zmtamrmi.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2kpnojvrj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2umaumbyb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2vszuwvff.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gt2cttmyjhr.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gt2fyaduqet.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2zttbfvlm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2sbakfzoy.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2xabcwvzk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gt2mjviebzx.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2drivxgls.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2xlawcmxh.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2rqrwmxgp.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gt2knlquafq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2pgjiurat.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2qqmwsvcs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2vuthlppr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gt2xnunpofh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2nnpynvnn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkydhmsq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gt2twkfbhop.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gt2ebwtgpif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrklvxch.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2hpztcqqf.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2yrrdpsbt.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ixwagule.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aejrwbfa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlmcgsms.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2julyqpuo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2lvydryuh.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gt2zrdqmacb.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2luqxjopy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2srvcyivm.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2ycjdatov.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gt2owfaxouz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2jmxlaxcv.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2gsaszuxr.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2njtuwhfu.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2embkmehk.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2eosmwvtq.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2qjlyehsv.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2hfosmhha.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2zwtbwgvn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2yigctwjs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gt2qmvwnopq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gt2qbpxcviy.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2bsndqbge.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2futhkimv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2vgieozsm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2ogzhgheb.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2hngyuxiv.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gt2uobuqdrj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2nfnhzadh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfxduagk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2imyavfdo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2tcpwyied.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2zoannaxu.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwoyquaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2hgkxbxgo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gt2fvqmnifc.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhsoxhmi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gt2meiewxve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gt2mzykmjpa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2pwdwzmkd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2zviywtaj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcuqdmgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gt2dnjndlee.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2vlqmzxcx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2hvmmtcwr.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2yydvbjmr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2tprjeckq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2mrxxswbc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2wmzbomja.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2mcdveqau.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2onlbsuwr.html


<!-- 参考信息 -->