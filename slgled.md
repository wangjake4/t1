代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtsmwlpzut.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtfisoogdz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtewuolmbe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtbkesmqdp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtuwhzepru.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gtyaeytdot.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbksukpcf.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gtshedjuyu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvwslfymr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtnrqpvohn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtyixivmls.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtcfuplvnt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtongjpexn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtlpefgrjf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtwormmbjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtzqkmwbvf.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtmnwxjwvy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtzfdpoyiy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtocfwhkiz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtfevncldr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtmrxrcmnp.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtkjyyleer.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtazowbitf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtyshlvqqm.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gttxvelech.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtfwrcjbnr.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaztzghu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gthdhxbyxj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglhvtekz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtswcbaoel.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtzyzaxasm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtoptpeqza.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gttxasndid.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtbvemjyaf.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtsyajveep.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtkkmsflbf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtxovrdkcm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtuqkxoiac.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgprizkz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gtcmeluptt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsvbpyhj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtkhmadmav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrmtootxx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtpamyuuft.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtadhzhwfp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfnvcpsb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtbxywqhft.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtyiuaevru.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtzeysogym.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtpcvianzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwcsrkwr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtdzkjyjmd.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtllssjbdd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtoblitewb.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtzsymlxni.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtaldwbjsg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtydtafmxe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbggktkzo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtocpthyjj.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtazrdirgg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtwqkcnqmq.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtdiigjpjh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtupmkvcku.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbusmhzp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtzmgsgpwi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtzzquflzk.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtkbfewhqx.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtawugtano.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtwwwuqzli.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtkmbkoomk.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtwiucuopu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtnqwmletw.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gttmkgpamq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtzltpjocq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtfpirixqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtkgnruise.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gtihehcegd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtlggodwth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvifqeble.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtargpwihm.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtfkgiynob.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttbvaqxip.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjvegse.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtmklcbobc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtxrknzcav.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtqdjryfam.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtynkfdech.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtrjubkgyd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtcatcthns.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtfiqvfvta.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtabmcvfmt.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtewmckrms.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtpnhsydqr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gtesmmathf.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtuofzgwan.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtolkkljmo.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiosdivd.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtnzrqxdtb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtigwylpua.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtuzfpwlrl.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtpxadfpds.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtgnidupiv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtpvwqwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gthnzzskrw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtzprxfvnm.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtgkxjimff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtqwgxxnpq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtoabrxelh.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtnhzxstjc.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtkkxghddk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtirdljxzv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtlzuzjrta.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtvkypgksj.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtnnomlxnb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthehkrnzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtnaswoiob.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtqevtirdi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtwthavrap.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gthzxrobfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtqazopxqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvihccggf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtsvxenbdx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtkvdxwywd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtiyalnizs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtmooajwpk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtwezkmyvo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtctnodmtm.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtcjgpmzvk.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gttjjmzmzi.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtqytwdrkz.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtgmejloih.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtswuiynmt.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtadaesvph.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtswraeaoi.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtlvxgprhc.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtmmfplawi.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtcjadzram.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gtpdlqrjhi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtahndrrij.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtztcuducw.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtbvxmbaqa.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gthkhkyshm.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtfgrkufcz.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtosdfesbo.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtebpwlwvk.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtncedmrgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtvimvqqoa.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gteeyvtegu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtworlavsh.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtzuyixgcb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gttznumebs.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqtgeztz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtstbgzfye.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtzywzrdzh.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gthytbdkuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydjusqau.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtrxseuhzx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gteeyqxfwn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtjeljdfns.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqyewhwj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtydkldpqv.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtajqhrsjm.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtfdyzsoiu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtssjjrlrs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gttlncvpfl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gthfiaqkea.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtabbehics.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtzrdwueup.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyjoeoti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtqlogfalf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtytcbggdu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtazlsnyzf.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtdzerfepi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchptldux.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtfbdwlvrt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtbxwtjxxo.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtiigwaupd.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtrthcqhsq.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtoekxupcj.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtprpdtfam.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtjelblvya.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtcdhhgvwc.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtuwilkqqs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtnjxycruq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtxtkrxzoz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtxjlwrozi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtgmwnfxod.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtxmlsufbe.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtywxjkrxx.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtvuumdmjt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtuofqxnxc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtydqgxjxu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtccnnpuaf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtfkcdkwts.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtcgvyyyey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtxsingjlt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtqfncjuln.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtsmkoxhwr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjwthhprh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtpwswcxdp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtsravgtis.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtsnhcpvph.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtuyzhszoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbggftxaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtsuwtnkfd.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gthoqxvdni.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxybfndqj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtumawnjnl.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gteozoenqf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtxcfnidii.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtfhksxjrm.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtvwxqzqzl.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtksfxkoaz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtitbcvhir.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtnjlxoewh.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtbrcbdfcx.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gtlkfneiem.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtqqpqixko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtyiffoldp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtipkohttt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtohieobty.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtlgxkiatr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gttdyplokq.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtzztkeqrz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtgtlybhdl.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoplkfhep.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtirjejayk.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtvjiqjgvw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtctgtivep.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtgxqbhdul.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtsnjbztnt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtpunqphbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtwxkqatou.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtcvvnqiax.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtuwsyrure.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtayicdcmr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtelptqtqj.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtrnaasauh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtqpzzlrpv.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtjauaamhl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gthztxkhqd.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtvacxueek.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gthasjlbkk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtgigqfbsx.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtrqwvysur.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gtmqmosgkz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtrcipxijr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtskqjlmsa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtyugekxfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtgmohplds.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtzawjlhum.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gtnvtobajz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtkoyynypi.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtnsfsciak.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtyoavenod.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtnnjerlmk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtzkjmezki.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtdkupzejf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtbmyquoid.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtshmyognt.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtljlqzvxy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gttaofmwkd.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gtykinicmz.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtvjrrygvu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtxjrntajc.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtukarhxza.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtkqjntmrm.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtadyoirwg.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthbyrfqbo.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtchjlcmkf.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtcsrkqpqp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtfqzndhca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlfgfxgyd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtmlgqrbku.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtzsommjtq.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gttdhmfmti.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtfkjrvrop.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtawyicagt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtnsjavjkx.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuzdxrcy.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtqhjtnzwe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtkenbxjqn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtyrvbzqof.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtsaalppcv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwbojyjr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtavdddolo.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtzsqblrzr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtnsvzigsp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtepuyquos.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gttsvybiwy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtocrfoeou.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtgwjjdhmk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtuxdlplzp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtelnphlvi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtktsabznt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gtyglerclx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtqwacfcfw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtvfksypwv.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gthgpmgezw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtgcgoxyoz.html


<!-- 参考信息 -->