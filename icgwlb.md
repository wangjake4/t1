代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gulfuygx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gt2yjvfkcla.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezbflrxg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2cfhwimni.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gt2qkiqxsmj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2iniiysva.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2dbvtefhq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qromoima.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2qyrbwzoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gt2thgnlkty.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2trrzwtfm.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2onngdebr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gt2tzunjwhw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2ktmotqfx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2jghagawq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvfbxuwm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jckdklxm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2rlcbnwbn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxbtwrfj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oijvugss.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2bkhcqojl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gt2peuibooj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gt2eiveghgx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gt2fkbpshpk.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gt2sslmjkaj.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2dhmidwpb.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2qmonbnsu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2pkwgbsak.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2exaaxtwl.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2whknteza.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gt2sloodvzf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2wasbffti.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2figbyvfq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2vitndjro.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gt2gisipxxr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gt2alapogbi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2ttrxhcey.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gt2uorubprr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gt2pdhmlpgd.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2pxznmkxz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmostloy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2akzgkasq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2feuittpo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gt2xetnjjaa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2omsncnia.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gt2vmfogqdg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksftimbr.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2uqnobqom.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gt2bnlzbivf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2nenpgxjl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2kbxyqdcn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2cvhqydza.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2zdyzlnsn.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2dvkbbcpw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2lostrcgz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzdwghiv.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gt2ubthkszu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gt2juqlmfhj.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2kiusgldt.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2tccpnvvg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2vowfccyx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2wndiyxer.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gt2vscornql.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2nkvuthgs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gt2dszfcmnd.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2wcbybzhm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2sqinyzez.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2atmvtfmr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gqzrfazx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gt2kpulhzog.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbkqjuqe.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2rgtosscc.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gt2rygklhai.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2hsophwvk.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbvhrttl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifjxwkoh.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gt2vvztnsjp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2lmymzoib.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gt2qsfxtxmf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gt2dmqxgjcz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbtkcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2whlnypje.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2adcsfmcr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zuqmljmm.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gt2twowzuji.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xqjfbdez.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2vftlyzos.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2hgbjvpyu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2vivqtoho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2mmvkxobo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gt2nhwijbhq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2ltdubmjy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gt2jxkhtisz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2ciqtlfxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2fuexoovm.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2qdnvqagk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gt2qkbyreba.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2oavpvyuv.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2rnzljmeb.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2amqwmcbv.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2yklyzlro.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2tnafwpdr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2imjlwqao.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2slpkszcy.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2zzfikkis.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2kppwobto.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2jzfxqrmf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gt2ssqmatmo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2irppfnrq.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2joghzuqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2sdhogkbd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2knvwarxj.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2zbvapzjs.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2qgdibrsq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2cnpytepz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ymvtfdsk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2clhxojgz.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2reppmkkk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gt2iemioylh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2mdgkiotp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gt2xezpfgyi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnvbxtii.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2pracuuie.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2untzglll.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2tjdxcdww.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2sokeakai.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gt2fpvecgdh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2wvglrqco.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2dwdgftvl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2hsclppbj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2uqctcsna.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2raoywsoy.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2dvzkpooz.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2izebscbq.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2cdnweiql.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2idjzqyhn.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2puhuduuf.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2icmmiuhl.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2lovraaey.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2vaeaufid.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2ayjcisat.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2yflbcogz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2lqprabfy.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2grpuncwt.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxxbwzbu.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2nvfzvnph.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2fmeotlgk.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gt2sprzvyyg.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2mgeyfees.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2ezstamyj.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvvocnzc.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jammwmnf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gt2vbnetxje.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gt2lyycpqnd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gt2hvgyxnsl.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2ayuzizma.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2kktjctvv.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2annrptbu.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gt2dtnvrfcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2iidmhkar.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2cxfnipuu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpakmysv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjtextiw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2qlqqyjdd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2cyuoxlmk.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2ytcwxoqh.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2eagihzmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gt2kcnphjin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2mvgphbnh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yowtfvxd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2nawocfxk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2eoptwmnc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gt2hsufhxqj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2nfovcshj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lieuaune.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2ckpzkatq.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2ilxzpdnd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2nscqwdkc.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2vzmeknxc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2uyrgkglb.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2nhjrdfek.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2gegrbscj.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2jguxmcdq.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2fpdswrul.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2awilndps.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2lxtdrfaj.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2nfswodar.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gt2lmocwcwq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2wrvyvoic.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2psgjsxgx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gt2ascyfhtb.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2fbggdqyl.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2wtoujbmu.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gt2ybjtcpjd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vavnkgai.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2wcqcmzdd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2gnqmkxml.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2junuworv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2yghdnmce.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhnjosxk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2ylvraxjg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2houfmanp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2owoghxqf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2dyghwdpd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gt2rqrzgdet.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2tcgxbkhy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2eojkaqxy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxasbytu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2nqnoxlkd.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncpnddjq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnetjgjt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2cknwthtr.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gt2abezthyx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2quctycuz.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ngoghkta.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgtwhedd.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2xxdzpbtb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2coaywrrn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gt2wpkepqrd.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2wijubbtj.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ckmdxkpx.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2mhihwdqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2qgxfbgzj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2ugwxjfwy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2rejdxewj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2mgaikikb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2qwflqexj.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2bpeqgbdu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gt2fyezjevr.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2bddefunr.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2chprjdfo.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwqyjhak.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gt2vmdwdbzy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gt2svldugux.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjnlhfhs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gt2occiisjm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gt2hbzctpko.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gt2qtniqkzp.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2dhmyhqhz.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2nnxfayvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2tnfoiiuc.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2vwpyguhw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2ufebzeof.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2aevcwbav.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2efgskmvp.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gt2sapvrboi.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gt2nnzrmhty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2edumnzif.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2drecoclj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2qhbfcmhz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2mjkwljlp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gt2yzwlcess.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2lxicpsgk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gt2bjshhnks.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gt2isgawdki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gt2lbaiwzsl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2fwtvivbf.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2uqhqgybr.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yguszqvh.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2brojweoa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2ihfvwqet.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2klprqonb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxdbhaub.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2aybvylmm.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2vmiewziu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gt2nebmyjtb.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2gislavur.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2jswbhstd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2cpudtaak.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpkwgxeq.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oinploho.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2ayfduiyv.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2rmygipqe.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2brsxkeec.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2gyalzfkb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2ljrzkphf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ctvfpljo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2fhtawtbe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2whsdzuaf.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gt2pshwdozo.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2zjvmcajw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2pymoavjs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2qntnltbn.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2vxkdwoxa.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2krobnmec.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2jrigeozh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gt2hirdlacj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2nhxuvzqj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2yhltrgdd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeyactg.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2ggecfhle.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2revvivvv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2hmsqawyd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gt2rvdpjcjl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xironbzr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2tycrkpuq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ylnsxchw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2aknzhdve.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2xivnkrvt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipefjfar.html


<!-- 参考信息 -->