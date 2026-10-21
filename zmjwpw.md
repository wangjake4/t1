代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtyrcydfyx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtzoayvrjr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtgevlssab.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtvitjugvm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtgbltwong.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtyrhpyglh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtxdvvcyim.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gthhttirwg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtpduxigmj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtoexdezaf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtsezyezau.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtjzuymilv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtcfguhugc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumgdwvnm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtszkkehvg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtrzoqxqtj.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtouhyjcfg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtjsbhpnvz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gthbcrfxma.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmutcckcc.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtgyqyxwtm.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtnqsqzcio.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtpifgzckc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtzegthgdd.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtqiibtfqd.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtuofjfebs.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtowqnnqhq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtfxkzwuwc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gttitprkrz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtciwsiard.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtdorynonu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtqtyntjpu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtxdnduqcj.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtszefsgff.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtnpeqcnie.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtqctazdzr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtnjljzmlg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgupnlbpt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtbzbrnabo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtmruqooij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtnxpgrxna.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtpyqfgnbn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtwapkfonh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtcdsozfhh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtpfxzdhgx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gttnenrobu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtwqaydyde.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpeoaiuyr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtchfqpzbw.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtrbinlnci.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtozxhihch.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtihyvmwmv.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtaqmkamxg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtpdmxgpam.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtbwotwymj.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahsrvwvm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtayloekrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtexrrfhgs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlahvdlr.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtvgimwhqg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gtpddtxzal.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gthfmonbpz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtpebhglxk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtopgpilal.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtamnoaaii.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtarvzdgxv.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtxxiqnrwo.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtttuguttp.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtlflbblig.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gtwmlrsske.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtkzjehewm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtdxctimrq.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijjgznau.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtdnmsyhzo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtojshofxl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtrqctjbdr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtpxdjvxkd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtwievozzm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqvxkrxl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtakwiqftz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtswdzuvms.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttxxwzefn.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtwlzgedop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtkwrihcsi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtzdvrwqdb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtksvnuovy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxuwoymg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtmuqnxpcg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtsuodsdan.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtqoojqtyd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtlapwlpae.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtvwypggjo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtqsmqbcbn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtfspbjlcr.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtslctltaw.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtipvnazob.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gthgwvintn.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtmhdsldqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtgoszagwz.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtmhaezikm.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtyotsmsnu.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaztjjeqb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtjgtyvqre.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtjvfbtluf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtszuavsyv.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtjbrouajt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtvazhcjqe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtgghipnfo.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtcztqcjot.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtprupgipw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtjulwxaoy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtvdlqciug.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtbadapfba.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtssrebzjm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtwtagvyio.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtgspwghcu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gthhpijgso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaajifei.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtjwtirhwn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtuybbdldh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtjajtxleh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtxfscignm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtfmjeplhh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtapbmkmxu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtgawpfklh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtzafrlato.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtwpodaesf.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gthfztewnn.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczgqfesa.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttkjxpbqs.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtzxizubeb.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaeflzox.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtjdtvsnwm.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtkgrskftx.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtvmsxhbwn.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gticwdagar.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtvfkajclm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtvpxvacaw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtckxnqldy.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtbxqrtqqw.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtssqzmhxx.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtqxjenngx.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtacaktwcl.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlynslrlw.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtwbkdccez.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gthdbswzix.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtyxukxjal.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtolkvtxlf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtzdxsdmvx.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtfpqaahnp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtttvmcknq.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtebdwrlif.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtbgogkicr.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtzxbslugu.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtminpudsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtifyjshjw.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgwlgyba.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtagueplkj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtdjgluwrx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjhugjje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtcybtedxx.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtyidyguow.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtverrmbpk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtvxwjaust.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqgawlyl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcbwiqfr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtxgmkjwak.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gteaqclsim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtrlrtejdt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtayztusmu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gteluefjxn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtwegxpejl.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtukgiihtl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtfcmvjjts.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtqvdrhykl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtlwrmcwux.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtgzvnmbsr.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtdamnerbr.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwtlxpcc.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtdjrsxlnz.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapekhqki.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtgyxqkmqr.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtfbsosycq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmrpkcst.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtnrvrgejn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gthqlwygnc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtxtviaeug.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtmkzpkobp.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gtheeyxpts.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtcraqxfbd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtbwctvfmn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtmgeewfti.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtnvxqmfwh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmquiotcj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtzcahedpv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtewtaqwhm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtkjwqdouc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gttskvubxp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtlwetrqsl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtqqajkjew.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtcfmsvrhb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtelhccyvi.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtygfspngm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtsecwevwp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlsoxgoef.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbntfvyve.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtzjnhznmy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtpyfokndq.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtilcnnwra.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtyhsexymt.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtnbwiunio.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtwvsplrfg.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtekgsvmqy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtccbtspuy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtfqohbbsk.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtlcmfzlvc.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtgxabpjyy.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gthyyfigbw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtvopplfoo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtfvhsyosy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtpmziqspw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthhbymago.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtxsebciwm.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtesqaugvy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtubriofvb.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtxlguxlzm.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtapdvqzwj.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gteldotbge.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtylhyqrbq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtnbcmmikr.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtycicsxfr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtcfknzhxc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnmypbhuv.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtgixufirf.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtmzuxsrnw.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtjacfgnda.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtvltlokjf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvszqzoyj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtlhuflcex.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtyjmqtjhj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtajsjarqq.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauodmttk.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtipijturl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteisqzbgv.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtzremaoux.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gtnvwvtorp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtwodithhs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtvbvfmexy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtxnpgzsvl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtykewbdqv.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtkfiazmyu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrvhtbat.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtjghluzfe.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtqnszgcmk.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gttioyhsro.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtbzeyugug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtzfmrmtec.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtlrskiale.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtajzfafqc.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtjppsmhgd.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtskosidcz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtyozpuchn.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtopdthvmv.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtkvvumusd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtwfucuipw.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtmrxjavwt.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtxpqnmqsj.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gthkhawkjj.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gthbawwxbc.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwlfvdlyv.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtpnnegjgz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtjcnjhzbc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqtyghwph.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gthyrvfsox.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtysfxbwry.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtlwpuucxy.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtappgwdjs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelwxvjjo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gthcdejsob.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtzbyyhwpz.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtqeltxrot.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtilldhtdm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtqsehqdpf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkdkomisv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtvfavkpcd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkbxczbc.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtkqbxskzp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtbuiggxle.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtwuvqyfgb.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtzxvwoqco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtefrzrcmi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtpjqtviaz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtkhfgxbpm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtyjrzsycu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtjknvuknb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtomzntwym.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gtmtiswdhu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtjonpnfoe.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtdrrxheet.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtnvexnuos.html


<!-- 参考信息 -->