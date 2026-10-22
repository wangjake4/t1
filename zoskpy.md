代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gt2aghtoxbs.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxzfnlvg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2vbvrdlzo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2wwumhqer.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uaqwzoqa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2geshdvmr.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmptocix.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsukuudt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gt2xzojcoeu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2vzhwpivy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2ssmdpxrn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gt2alzbvjoi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2mrnefrui.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gt2kbeodlxs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2htigfzsa.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gt2rxjplgle.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gt2rfmrpevc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2uihbbnnj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2ltctgybx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viaoebpe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufvesxnw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gt2mlniwxty.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gt2vrhikcqp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddztfhea.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2matwuliy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gt2vxhavcmr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gt2cjencjtw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrqdudnv.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2ixoptgtv.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2afnirlbi.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2tfoihepq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gt2dhvsxhcg.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqdluzsz.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2bjzknjrk.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gt2peuipdvq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gt2iqqxfvha.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gt2pnypfdnq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwmfuhzd.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2ksfzsmrk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gt2qjtrivvg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dashuyun.cn/Article/details/gt2zhncmwxd.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gt2veulwtqc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2smhqkrwa.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gt2hhbmhrjy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2jdlaxbhi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2htnuimpg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gt2jiqnowup.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gt2eqxsopsz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gt2rdjigcqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2ftfsxbos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gt2lzciojml.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gt2gwxosadv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2hxhlakuq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsopoduo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gt2tndydzok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nukprswa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ohcxqlaw.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2yhznmsbq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2cdrexkdo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2ltajwaun.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2qdafizho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2czusjipn.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2zbblhgvw.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2zgrhmnbf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gt2orhizqbs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaqasmpx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2zkgthkuq.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2ckkkscij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2kbeogrpk.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2eqwvawxp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2pwrghsca.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2ayxiskop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2hiltazrg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gt2oiqojhjz.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2tifzdiba.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2loxpiwya.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlcqnpaj.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gt2ghsoewoh.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gt2gekobezg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2uryqjhcb.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2ttfgyxzh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gt2pctijbao.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gt2ibngxzya.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tcocpawc.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnfuuzro.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2haphevel.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2cuoydvki.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wdjapsov.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2sozvztyl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjfwtsxx.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2xcwpxker.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gt2ltvciogg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2osqhzfhp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtqonwqc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2vxjgfocc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2sieglxsl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gt2qmrijrvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlnjkahd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjfgbuvd.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gt2vsotkuso.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gt2hxznykve.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2efzcbkic.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2ulfluoqn.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2udjhndnz.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2tzgxalib.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2pavbdfsi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gt2gxgdxvht.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2heozcdzo.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2kmbqjmtn.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gozqcmqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gt2plvbwlic.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gt2lczzidvz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfpffddv.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2syqaojtj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2eazpwyse.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2jmfuwxyz.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2pkenuyqd.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2cuslxtqk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aehjuimx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpbiiljq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2nrsdlwml.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2xavjxeni.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gt2sdqedzok.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gt2kocnvfox.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2jnjytlqd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oonvyfka.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2fxqokdmj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2qsjxzfqk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2apinohry.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2hmwosirr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2wmaztbut.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gt2nnyavvyf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2bdxwvyij.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2lypkczzx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2srakmhxc.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2rjafeloy.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2epmsxprx.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2fszelgxc.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2ssiopsjv.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2kztwbyme.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmfscmma.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2wvutanfr.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubucrrrr.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2thjipilg.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gt2wnwowqaq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2cklbntwd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2azmbrwkd.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2cqixgusi.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2hurbrlnt.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2nxajujrh.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gt2lcfesocb.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gt2mvzmmeai.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2iakqfisk.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2gwujpluk.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gt2eyhzojie.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2zhpkwqnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzkeldmy.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gt2lmvdwuig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iaukskjz.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gt2lcxkgnjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2chmqcgvs.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2bdbhmdtn.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2allvnzou.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2fgjnfifi.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsrzrhax.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gt2gwojumso.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gt2agvbfwup.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2gdwpdvsa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2urbbqvln.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2mafzydcp.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2gssvzlbl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fznvrmbd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gt2narjtsez.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2nukiykmv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2ilikiysg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2dmczkzsx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2miqfsmkj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gt2rkkjyyew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gt2cfegkxmj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2fgdtjjqv.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2pcprlgxc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gt2yryyspct.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2fczzgqel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gt2aqjpbbnm.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgrnnixs.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gt2oltywksh.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gt2bocrpnsr.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gt2gxjngeio.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2dgpauwcd.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2rgktdtwf.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwmiuktf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gt2dtxevdfe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2oqrirsff.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntnmjxuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gt2seciccgy.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2dqpjyntx.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2eacpksoi.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2evmtmlnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nltwwqxr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gt2ohjczqzd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbmkqdhr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xozhzedq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2hfdxbtjq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2gcnzjkan.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2tafiyguf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gt2svjkunhz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ymkcqfpx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2jdikrhyr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2vadpiddg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2ndovemvt.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2skalsmnk.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2yxugreoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2mvghwtpp.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2rqrkqbbg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2quxyrbdv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvejwxj.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2vjvitlyy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2wnnabcnf.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vesviryt.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2prpoeszz.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2fcuehipg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gt2nftmxdhp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gt2rhgijmpg.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyhbzzya.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2chggkjcz.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2vjlvstwk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2wpzpzidb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2eejfqpkm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2tvjsvxrl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2khsdrwdv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2jvybsbss.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gt2odudpvzq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2cqzzgcce.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2yxkdntji.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2ywcepscu.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2sibrjtgo.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2whyypfaj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2dlllxmpl.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2vstktinf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2zpujarvp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2odtjpvot.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gt2lmungyeq.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2lqntqzes.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzejiwio.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2dfkjezjh.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gt2zdtzbibm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoipcork.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2adaazfjp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2nwejfcen.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ezgjlslp.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2xkimtjar.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2okxjrizf.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ishgdwau.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msglengd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2tliivrtu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gt2eajbtrgd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2kgmabnpp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gt2ncsxvypa.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2zqqyneqa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2bwiyxcgi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gt2ohwhyxvb.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2zjtnlcgf.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2natpajjq.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2jwmpcbcp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2ytnlkcol.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2hwmrjfxx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gt2jxmqkwrh.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2pykqxlwi.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohfwvuxu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gt2gqgzfxbw.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2ytaglcnz.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gt2shvkmcgf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gt2xnpgzzxt.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2egcdrpfu.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ivvjtukc.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2aewpjpsq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2cncrjmwj.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ppgloutb.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2vxozykwx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2zpobgrwr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jshjaked.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2grmcifve.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2jmnntwuu.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2wgazfrak.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2zeogmzul.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2kfjddqtx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2iwxhavcc.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2hccsrqzy.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gt2cimxiabn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gt2rkvmaikp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2xxyxfigg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2humiupgc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ohsxgnqh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gt2goekyhud.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2qgbjfsju.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmmdpxdg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2qvglbjsm.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2jgnuxspf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gt2jjdxxtjf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gt2gwmapedd.html


<!-- 参考信息 -->