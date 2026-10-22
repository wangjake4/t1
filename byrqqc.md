代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2zoowaxvv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2uksktemx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2lhnwyyhx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2vpljfijc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2qyqneoek.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2aolcskoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2ktmwoean.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2psmrrrdo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2odniuoqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2dxcdvxvq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovdjakue.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2bxcggccr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2ewqixxhj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gt2sifousmf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2eenmpqdn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdtgmulb.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2bqwgcyez.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gt2gxhfdqct.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gt2uhsfqnou.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gt2hjfyxsqd.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gt2sbosrmao.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2uyptngbp.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2jonhrpky.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gt2croqnomm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mzumhabv.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gt2fuakqfdh.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2yuydcnry.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gt2xiizbomq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gt2srzcabwy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gt2yxzpywes.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2ioxlxjsq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gt2romijckv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2eevrjdog.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2ztrepxfr.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kefhqndy.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2rsibfmcc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpiiwhsr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2xbmdxjca.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2vqkxzmvm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2wwkwlfzs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2opjftlwp.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdbnypmg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2spxddggo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2ioxruryr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2ubntwmnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlpxowsh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gt2ldwxeguo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tspomzst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdgoaxny.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2sxjrglpf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2qpageqrs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gt2vqdrkjex.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gt2wfqmgwkg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gt2hedazpyj.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2ucbsqvma.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2cqkpfydl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gt2umfjpbch.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2hdcivbhy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gt2atcbyvoq.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2syasssun.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnkfcuob.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gt2xezsukpu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gt2lfwbtscz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2lsgaxbxh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2flurmgvz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sljwsrzp.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2vvwzmwka.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2dnbsfusi.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2jttmpbon.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gt2dlamhfgd.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2duiadfav.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2zrdpanbc.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2eoqwyrwm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gt2obkrpkhc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2yqwdwago.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mfkfrnwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2qwuzpljh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gt2lmdbehwe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkeyvzzm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftacwonx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gt2vlrqrsse.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gppqstoz.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2gnymimok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2ebmczimv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2ndqbnirx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gt2vzvieifn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2sqhzelav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2yamgsluc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gt2czjmpcey.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqpxqmox.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2qekfwafv.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2lfhgvxwf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2xrurjhvq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2cczvgldp.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2rycocbnc.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsxsbwjb.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zenfghdj.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkattxbm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2nwddjzsw.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jltvjwqi.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gt2phuewdzu.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myhburkk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2nqphnirm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gt2uvkhzufj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmcoixne.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2gtpnudfg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gt2yvcctzov.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2utxchilo.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2sgmywnok.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2puhemidp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gt2yxevevyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2viyrceou.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2emsroqvd.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfqyzgkj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hubihbvq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhvlemvv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2tqrvzqzs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gt2mipqllka.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2cgjvasfy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2vxkacfue.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2nudwxeyf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2bvexfycq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gt2hpcgyinm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2hagclbqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtathahq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2bwiqjdly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2bdcipxhw.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2ftmdejzp.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2dmpbizcq.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvhkzeyd.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2tgmvagsy.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2nroiiatn.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2weupvofg.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2jhundyqd.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2eoiuiyyt.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gt2eikogtad.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2ocvoyvdg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2xnbsjuba.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2plfwyqnn.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2lyiveoqx.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2llxnbbob.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2aexwsuhy.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2wvrsgofe.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2hlfyrzbf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2bkztzvlx.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymntjlvi.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkffyphj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gt2gnmrskup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gt2tceakttj.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2njwauopb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2mvmlznnx.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gt2pzqgamqz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2xzqralhz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2ystijtid.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2ykgdrlcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2xgslfxzf.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2viqunuod.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gt2yemnxrkk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2qnpitdhq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gt2ixjhxvel.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xyymhbsc.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2svsyeuar.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2cmvzkqsa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gt2bwngbafu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2mbsxpiqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gt2jzaxazzq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trjquitn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2odvudjeb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdhhbcsh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqovlfym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2hyprtowk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gt2hpafyjoi.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gt2dbrgyvfu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gusqcjoz.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhmtbxob.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2ckqpfbfi.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gt2gbproqde.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2pormwdol.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gt2urjxyubo.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2tdcrjabw.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2tsjdakzv.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2cugqedry.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gt2phpgltpa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2pydzthxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2asfiqbzm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2ewzrjmxn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gt2wrjsdlwo.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2gzxbuqoa.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2tjvwgobn.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpntbriu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2paurrllc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2ifvgrqlg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2sfhhfhft.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2bjeeyznb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2qlvhztoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2smyoyouf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2wzcpkglz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gt2dfedpibj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2mucltdme.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gt2ifyckonh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2ibpfuxbs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2oporfolz.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wuzqxivo.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2lcytzkfj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gt2kifaubin.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2orrdonpb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2dmtbries.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2wrjztavd.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2ktnygens.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2iygkjmfr.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gt2qqkwzlsi.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2bphraxlj.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2hjzregwl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2niyemysf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2qzqqhidm.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gt2psjhzghc.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkutvgmx.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gt2ylplegsd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzesrvyy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2pgpzvgjf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2xsfebexo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2vmirgmeu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2lqqjiydv.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2uycofsxu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gt2iuahkkij.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gt2tpqwqkpy.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2iodbvyih.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gt2bzfefghy.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2lnxvygib.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gt2mrykqdgg.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bkjxeoot.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2lbtvukae.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2dpqxxaus.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2qzkqjgrx.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hahtszax.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2ascfxxxt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2baxfnkvt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2wbmmolfs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gt2luyuxssi.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gt2ejpltemi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gt2evrbwzmf.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2zqajcgxz.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2qnnqdpzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2pbglpltt.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gt2zbnqfnfw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gt2ycdptcby.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gt2rskaihhz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gt2wpwsvncv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2xfokowip.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gt2bicrteqe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqdiivdg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dybicodc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2blbjptav.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2mwgfkqtb.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2vngxezci.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2pnjegmuh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2lzsygfxp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2fqqjzuky.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2ymwcbpmi.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2gtvagxky.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gt2ogedraku.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gt2jcnbysyd.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szqdlxso.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2lptxzjpq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2pmqatweb.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sygbownh.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2vjbuslgf.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2vgpfhoru.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2yppnatln.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2tvlupeid.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2gtwzvzur.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gt2wiwoqrib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2yhnpxjfb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2tlorekch.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ctuqntnr.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2ldlyxviy.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gt2ogedkgwy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2npkjprjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2hlhjfobw.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2halkgqeh.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2kktlvoyk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2rsgwytcx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2jgtptpxx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2pkftmebk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2ulziiqis.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2knzvotsp.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2pzuupxph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2xzhkxasy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2yflidbxt.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2icrosdpc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gt2nfscahvp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwhxoveh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2anrltdha.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwwjczdc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2keuesgqi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gt2ydemkevx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gt2ibfpeckd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2sqjuudpg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gt2heoloapz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2qthzodfm.html


<!-- 参考信息 -->