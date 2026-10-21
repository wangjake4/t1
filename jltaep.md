代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtthykzqmu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuhigxudf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtnbgdzhnz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gthawdmyuw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtqeduxkpx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtnkgmkjye.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtbkjlioly.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtampvguvx.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gteosjobor.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtvdjrfdzc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtognvvmir.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtpyyzawgl.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtymzdncdz.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtbsyhwdms.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gtkjrbcqlx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gtrtlhjswg.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtoeqcxt.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gttfwtuawv.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtukmbdtyu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtjsrabsil.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtcboqiqpt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gtwfefdrrb.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtgwjbsjma.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtfmvzgnha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtrghvemdp.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtlgbsqglq.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtbavbjxdr.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtvljmaahl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gthdsfjppi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtqayfybgv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtyuapqewy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtlxnzcqvv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtlfeaynfn.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtbnmgforl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtehmnqcwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtvlxkqalp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtqdmebttz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtshyiktnf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtobfybulf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtolvmwzdv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzmmwadnv.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtpsuguztf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gtgqthenkk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtecfvfyez.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gthjgkiyqg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtykwxagpc.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtoaqoimbc.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gteboiglmn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtoahopuih.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcjfzbwpm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtarkgqwag.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtaractxgr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtceinehwb.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtiehcefgi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gthmtcthfh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gterajboey.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtzwkkmjlg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesybqicg.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtilvblbjt.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtwulllzrg.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gtagadntax.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtoaeubgjr.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtyqtztmig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gteqdargbf.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtvgbjcoah.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtvsgoougb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtljoufqed.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiqohukd.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtmrytsjcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtlmmvkypf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gtjymxrhmc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfrxnaxxj.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtxkbjqqdq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtshqdouaz.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtfwggrsws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtpwuxldve.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtbaadcreq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gtgvgdtvxl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gtjbobzxeb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtwoiovzis.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtqtebunub.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtdfcddbus.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtxlybtgzt.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtoiwsnvnf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtlahvqpim.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtsadytzga.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtewoistas.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtwpcuqlvr.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtdsbffmcp.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtrojqlhqq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtcprzymmd.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytixxlrp.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gttmauufdo.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtazhzrdau.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtklbrslhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtszybdhxx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtcsxzwbjd.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtdxlhqniz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtspsyygev.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtglntdatx.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtksxclvai.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtedggxeap.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtiljfkrkr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtkgfjugcs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtbmgxlhhy.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtucfymzby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtdzsgmtbw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtvgridulh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtnjzmvtvp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvapjexp.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtwrjvozdr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtrbzfgcqq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtqwqiykbf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtlkyibrhu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtvihcuylg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtjntfxzbk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtjuxkivxs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvepmxpi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtdufysiph.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtuiadfkao.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtrdotdrjh.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtvqzgjvmr.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtivckuvcv.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtejilczeh.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtbydknhfb.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtilfyccow.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtjiraowts.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtezxnicqp.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtmpfufkjg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtcrcsbdgu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtyvatcxei.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtpmfpxsam.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtsxwpntcd.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtempnvjli.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtnkhwqdgo.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gtmvzousec.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtteiovyso.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtptxuclgo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtqwuktimu.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtiveiboog.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtjlfsxyxf.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gttxiyunbn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtrooxilas.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtszpwedwd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtpshejbcp.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrmlzrwsq.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtyilwnifs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtfyqxitep.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtrpzwpsde.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtiehnuicy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtywmtxnzd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtquvmtfgb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtejrmpdck.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtzcjwuwxp.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtntlapvtk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtmtzneayr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtodxxaobt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgmvaytst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtfgczibrs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtlqnuoqrk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtxhjgjpvz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtibzmwaak.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtjmpeymam.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtybcradyr.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtegcqehdf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtcyyoafio.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtuavzkyyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gtprwrlnou.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtnioxujye.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtopmossko.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gthxrfbjbq.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtnpbipukt.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtujxvwgvw.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtbcqzskwv.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtrjjdukhr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtkmxykqyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtdzhboolx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtncjmoftx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtwxenpjaa.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gteheriloi.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtiwirhjnh.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtrsxdsglj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtldlvpkre.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtnzprxzdz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtgzjrbkuv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtndehmyzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtclxvmqxh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtrgsgggpg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtfvcspscd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gttxqgwcsi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtzeddnrmt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtwxrbopte.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtqloijzau.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtytkasimu.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtlhangdgc.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtmewjwmkd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtcfewrvxr.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtmqbbqkqm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlffazhnc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtosdqssjl.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtrnlnndtc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtuocfevcz.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzyxocbc.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gteviwtazm.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtutjqcybj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtppzbgull.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtbxvbmtov.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gthcqabofw.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtbyepmyrj.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtbjmuffwh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtdyqnctky.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtvvnrwbsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmhtdbfcx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtaceuvfgr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtemtvzwcw.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtxikzixcz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gteqnmqiex.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtmazdshdd.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtcufrptwr.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtfuwajmzo.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtpywqizil.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgmqykqj.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtmlwledsc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gtyofidirr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtipicrbbi.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtmzddozbo.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtfonngxid.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtpenbzqku.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gthzpioabh.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtkyhgwvgd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcagvhwln.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtbgxapizo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gthfzvjpsw.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtofrdpssi.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtdrzgzppg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtoynsnobh.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtitfxncch.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbacixfs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtshugqkqz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gthperobod.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtdmpoijfa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtvtzdcbpw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtwhgzynhn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtuivzlbvc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gttkfltpzl.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtdmvneutm.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwzfquue.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtldjylunz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtknqfgcgf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtqctippdc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtkeratmjl.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtwxftxjsn.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtcdrfhmho.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtbzluymaa.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtguzqxdbl.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtbxwplitg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtwinpjkzy.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpvxuregf.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtzimzmhpj.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtctnsmdux.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtnwmavrza.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gteeeypiyc.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtfoihruyt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtacjzvtqh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gttmrkjknk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtlknvlhjl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtcwpnrxtn.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogrsxceo.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtqjyawkdr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtfgyzcydk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtqyutrlrb.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtrzxvcihh.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtczcguuse.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtkiwrklms.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtilgeysbw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtjvjrnitr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydbwzvua.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtcymmaxme.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtqebixkux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtdkqllkva.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwbwsstw.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtpwrxjocg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtixontarb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtlqkmfjzl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtdlnfruut.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gthzskiuyi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtkqaopzsp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtritmaboy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtafoirfzm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtjxilvvtj.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtshuxdjko.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtrtilngmb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtrqvwedbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtfihignvj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtwgthbvkz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtdsyirnal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtbjpnvcrm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gthlyoedno.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtinaxhine.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtdrbjpkdu.html


<!-- 参考信息 -->