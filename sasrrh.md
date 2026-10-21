代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gthwyshhfc.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjklyclrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtyhotkaia.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqpemchl.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtrzvpcgfu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gttdurlmyw.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gtfjslrmvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gtrnodjqhe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtlayrausl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtlcibllqg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtgdzowssm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnygsobcq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtnfntvmdf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtggkvabdu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtzksttlkb.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gtuvzmdafh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtibpdqyvb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtrmimreae.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtmfockpbj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gttsldqkio.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtkwjtesvw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtkkipetgf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtdefpdawg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gttwczncai.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gteqnztmyn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtdliueeck.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtlyfdvzuk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtfpvkfbsi.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtwyzteblf.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtwvpazbnd.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gttcdnslxz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtbprzjaab.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtsphbyssp.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtcnkygxbh.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtrpvbqpcx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtfnrnoliy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtdxjgwfae.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtjizxqdqm.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtxcnkvyhz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtzctzchlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtrbawoxrl.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gtklgpproe.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtnzjwnryp.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtlevedkaa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtvnuhotdz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtvevzqbnv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtcnlpygae.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtelaviduy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gtldxsgdja.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gttczipiwd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtuyywhjyy.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtwgwdvslv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtagghebtw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtholytzue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtjmzeomfj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gttkzwzmvw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtekkpijjq.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtqrehthmb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtkrmtwujk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtkzxpdkbd.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtntxywbxk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtippfiaer.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gttpcjhhir.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtqszbsjdl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpsiyxqx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtqzujfwcj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtzklxdqlu.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gteduybrgi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtolqhmkal.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtuvabgcij.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtukqsqhqy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtafsuexox.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtaedyenuk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtbusezwcd.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtbrhlkwzn.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtpjereyou.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtatozupoj.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtchthnokm.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gttspghdds.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtlpumlshp.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gtdxrlnveb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gtvowetppf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gthcmecsvl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsakqybbz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gttxzihrje.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtcsvjjuqp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gttrbgtnbk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmteodipk.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtemuincch.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmvyhlokt.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gteasnnkwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtsghhxpgh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtcofelooe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevpunzmz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtvjncxzak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtcnziqkwk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtawvhqouh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtvrycfcvx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtiotnozrv.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtxsvnueqf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtlzkpwawt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtzowwysuh.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtrztmgmin.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gttcfqtflv.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtxvtnxhpe.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtvjynmihm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtwvvnyblp.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gtqwtyushr.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtkgadtpke.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjrgncdzh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtolxnbpmy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtxvctgypt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtirpayowc.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtmsnrontt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtikicdzxn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gttqcevgii.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtentiadrq.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtyjendigb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gtzjkhwsru.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtjtcvtcbn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtlwoaxbai.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gtpbvbfudr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgyjyadf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtfxiwenmw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtaijzzhyf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtvnobyumn.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtazqmxvgp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtuazhczwh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtnlksvneq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gthjzpjlxl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtejvnbbzr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwplkhxvl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtppqcpsnu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtnebudmwc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtbsgglzfp.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtwljrngyp.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtebotgvhe.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtupqezqdl.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtkygoivgh.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtkmmhbuuz.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtprepgyua.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzzhtcpby.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtbxunwggv.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtlzwzxsxd.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtkffmviwk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtdwfdxici.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtgzldbdpc.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtbmismweg.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtzdfwynlw.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtibrksmid.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtoqqrahwr.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtpqgvezif.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtykhcnkdw.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtpfejnpyh.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtzoarrleo.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtixyugfvy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtdftfhagf.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtpkubmjsa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtptaohuhc.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtekgxncyo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtseffbknd.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtikcllzve.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtxkawbgir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtfadvkvpt.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtzmrtewtq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtgbikjrxg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtajhxlyfg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtxmyagbce.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzptpqbms.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtedmwvbsu.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gtdkyfyzta.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtsigxtyro.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtqywynszp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtmpukzqgj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtzjsjtjze.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gthipglujc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtckgdfdug.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtzssxskoh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtbphpupha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtslntpzgv.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtgwfdsbtb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtvadwhfge.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtqffbzywt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtuvmbyvey.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtvnxnlpta.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtefchqkth.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtequpnbhk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtrxsnlift.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtzezidtxw.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtfsfyxmii.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtfuaqlxmg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gttalyhgpk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtmuuwcahb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtagldbwsu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryoguaig.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtpiodrupi.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtyqppjgqx.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwobcawtu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtjhopmxhs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gtqjsaskpl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gttdtiuxvu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfynxbcai.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtaxpisblw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtxadsigol.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtkmbhoyyo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtxirjinhw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcemfihhf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtxpnlcpzk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtoksolkuu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gtcxnjkoqp.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtkczcqvtq.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtpxbfsfig.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtzhulgbud.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtgsqfozta.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtspchmnxg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosildqao.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtcezafxon.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtrfhlxqig.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gtzjzwlhjb.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtwkllrlyc.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtrjziaieo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaqnecci.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtgojjwcdt.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtazbgdefa.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtbgpejuue.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gtzlzqkzyk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxlbbrmh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtohvqdumh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gttawacoiz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gteltcysuc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtwpuwcjwy.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtxinxrcpv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gticupwsmi.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtvsuecdxb.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtowdkgyqz.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtmtuferen.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtfasklguc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtwrcqgeuv.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtavsckptn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtrwmvcbxs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtxviiuike.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtlpafucwt.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtwpcqfvnj.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtzatycohd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtgcpdhmtl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtrcvorsop.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtqtpjwfjt.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtnubywjmp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtnzjptvrh.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtqzkegrju.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtemypeszs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtfzotgybv.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gtbawfeltx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtmwbyzohr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtykdeaqqw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gtzchywyqc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtheyjwhiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gtlwtvrecf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtfkdfbena.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gthbkiemcn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gthaoqjwpe.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtojznjacg.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gterwqepzf.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtgmdfvaeq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gteqysnmgy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtoyhvcltx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gthaoheotx.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtnunmwshj.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtaefaozrv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gthcvtzgka.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtuvgtqfnj.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtipquwxim.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtotsicyer.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtsduyxmkx.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtubxeisun.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdgpmokyh.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtjswqnjsk.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtoyaovlqf.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtnxekcntm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtliigjqkv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtfzirwlof.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtciysesmk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtapnfjabj.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtwjwczuft.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtzzihhpii.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtkwxeybzf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gtzmkqlpsi.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtgcsjoraj.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctmvaxls.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtsbzjehbr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gteeujdsbd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtdnqxicji.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtghblorlf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtbpnsyqrt.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtuxvkdjxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtbrgfsvhc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtnbuubodv.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gttlilsgfx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtgssvbyey.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttfjedmy.html


<!-- 参考信息 -->