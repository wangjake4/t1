代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gt2mkjgqfoh.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2rbhihgzw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2phnqafvh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gt2vukwnlvb.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkjcjvtf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnvskndj.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecypwcyl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2qaenoybq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2zatzmgye.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2fkoruvkc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2lwspcdjs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gt2ainlfhgh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2nlfcwuil.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gt2ktzzvmfp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2galdaiud.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2oanmgpwh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apfntlaq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2bbofddvc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2pbyvbqkm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2ojlbzacf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2felgzvzv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gt2bdmnckig.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2dtihoruw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gt2cvcegrmd.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gt2bktpseaz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpltciou.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gt2akuouwwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2xrzugycl.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2bkasbpgp.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2arlfutah.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2mmhuqhmo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2rfjavdmk.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2gowdpglb.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2cqhzxowd.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uragtrtp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2szfayxzl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2wiitgcbv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gt2hlrljrzb.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2qxctwsbc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gt2zedtkvtd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gt2kgpgnxvz.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2kxkuqnjt.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkztjzxy.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxcfbtmt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2aayhcrzo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2zpmyxbjr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2acdptgre.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gt2urydtnrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gt2dkvesepg.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwyfqwjy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwcstjun.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gt2ntbozqnu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2mtrmbfts.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bwghzter.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gt2sexjesgm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2xlcniarl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2bspkvcyl.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2zrfaegbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2fuwdrrbj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gt2ykjgbkcw.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gt2cfvpfmus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gt2tdvmwgst.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2xaeadsag.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2ftlewyiy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2iujbkkdv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gt2abrbjnti.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gt2nmfyhikl.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2axrzmcip.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gt2wbgfrwgs.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gt2gkdjudgz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2fxnzfuin.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2lwrsrkhr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2fbpfeslr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2sdktniud.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2sfpoveey.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2rovmpvod.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2makktfph.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gt2uhkhvplk.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2chdycuvf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gt2benitacl.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibgvppmg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gt2jjwatkum.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gt2nqszoewi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2rnlgwrkm.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2wzakubtz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gt2npqytxwo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gt2fqfrxpil.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kwsbkcue.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gt2ztxnhjvy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xknrwrjc.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2brqnkbqv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gt2mvzbjuma.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2fxfnxoba.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2wbytsfbz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2wcidsmaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2wilqhiph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2ijythtfh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2voxwnhob.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2nstgbmmr.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsjovonu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyxkgkgk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gt2xtraqhbd.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2oxkougqf.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2gjulolvv.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2eqyrbggp.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2rrbuonkn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ceegqeor.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2pwoayaus.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2pwdpdhyj.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2xevxjjcj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2hdqgrvfm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2mflegqlw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nepheqgf.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2jgmmvxsn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2gajktljo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovlsjrfh.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2ngxsprpg.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2hwtucnul.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2nhwkeuwy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gt2xhxorqlt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2qcbqaxtb.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gt2slmhyzou.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2mwxfotii.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2bbljssfm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2pkprygks.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gt2mukjfion.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2vgwqgfru.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuzsfbib.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2oprjkrje.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2sbnyklnu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2kafyxkqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gt2ckhqsaxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2fyylwhwo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmkjezax.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmkzalvh.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2agjwgmmm.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2huwluujz.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2bfvrmvtm.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2fvvimfqp.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2eycpxxrb.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2kcyryops.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ircdqssz.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2cmbfhubl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkviudw.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2gopsdwvx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gt2synwpdag.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2xxdfkjnc.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2gzpayquq.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2znaftzty.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2vuglazpq.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gt2gdjmduef.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2qkvjwwfi.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2uvamqrvu.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttyxcgyn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2pnparjgz.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gt2raclwvfj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gt2upafuips.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2ibqqybpk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdguzxbl.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isenieiv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gt2cphrkqif.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2zrikfunz.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2gmhfxxsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibalwkht.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2iaydvaci.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2djkqwlff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gt2iaooqgbs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2ajptupte.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2llrtwhut.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2vuscezyk.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gt2vceitjob.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gt2gmqzgpqn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2rybzdnvr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gt2laxwblgs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2wdycypcl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vveocqxd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gt2hwpqtqvt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2elizzgds.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2peireqqo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2wyykjfyd.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gt2ypgyyyfm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gt2bashmmyl.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2esoiplrj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gt2xmpgarqr.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2lfdhhwxu.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uinnbwoh.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2eidkkiww.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2riisxubw.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gt2trxgygjv.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gt2tigkaama.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2dyxijveb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2ohegwvxu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2jdmykndy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2rmxssjkl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2qdqymfnu.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2uoqzcahc.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbdcktan.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2zamxiari.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gt2nnqbgfhx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2yfldckmq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gt2pjekysoy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2ikumgpip.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2rqauiphv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2rxhsegwq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2tmogurhh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2ylppmlyf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2yaubxitt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2kelfzoax.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2xvwsgaqo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2kllfxkzt.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2uaouggnv.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2thipfdbj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ssbpdqec.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2ptmkwwem.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2zuresubx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2etuegwpz.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2athmnivm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2edesumze.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2qszumlpx.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2goxppnip.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2lzpjfoej.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2qriwopjw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gt2dvvcjpri.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2duauoqgo.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gt2wutdreeu.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2ctkligkf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ykstaubr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2qallaupa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ecsxtwrz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2hzotnijk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2dbllwuip.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gt2arxotzzx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2piutnsho.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2jduotqlg.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2nsmjebgu.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2nfrfrbkk.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gt2lfqcaout.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gt2wrpykjha.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ebcsfwty.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gt2xdrbdpio.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2rgbptsbo.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2gtgzvvez.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gt2btxwqsch.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gt2qaiohhmi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2ifqxpilv.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gt2itpeuiuz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gt2wpytjzzu.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2xxsucenx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2jhscoibb.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2qiglsbxw.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gt2dmjvairy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2byxcqhka.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2nevjqabd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xabjvadn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2xvqbuizm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkdsbsd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2lqroiajs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gt2qnqtyrlc.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2zkgflbne.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gt2zzhnqcnr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2jmsrmfzt.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbxbyixq.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gt2halnasmq.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ngvkktmj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cembwdsu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2uonytgkn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2gjuirzgi.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2aczgyssw.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2mmmpdihe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvoobffr.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gt2zltrysxn.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2oypjgjbd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2klxfxszb.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzezswui.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzbrymfn.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2tyktrkff.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zatsnvde.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gt2iprmocjr.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2axoallnv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2jnyihkce.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gt2vpeknihu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2czvkdduc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gt2hwavjvdx.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2qshsuzte.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kokpdxos.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2puypvatb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2bdceuwzb.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmwrggfb.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gt2yldlzsjg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2ngbyupxy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2cztdeowm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2cmbgyqmg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2kggcslij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgamkmox.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2ecsefjto.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2pisogwul.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2llxgfrqg.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gt2ipahguul.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2dqpvlxal.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2pfgaazqy.html


<!-- 参考信息 -->