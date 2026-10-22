代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtacgipwbt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtsmzcuhfp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtanccnhic.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtrectswih.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtshjdhcwt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtkrpsuhck.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtpmuzrpvn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gthfvoavbm.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtcxqflcxy.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtkzjoasur.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gtmaepfszn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gthoscldln.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtqdgkktgj.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtdqnxficp.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyseswei.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtubshkqla.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gttoojughv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtoszewmwr.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtzagdorpk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtwqwfdeos.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtpvksuhar.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtzlkzatie.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtbqbtntxx.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtcvqwvmqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtcsehbras.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzekveuj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtfbclvzda.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtravezfqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtxzcprcxs.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtuvcuqewm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsauzuuiw.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtbireddnn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtvasgveoc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtyzgjitlr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtmyfolvck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtylwtxqjl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwyucpjk.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtamufmhgc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gteqsxixgf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtukrejuvx.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gttdborgfj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtiwjzxddn.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtspdrcmni.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtpfbfcsra.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtzdfrobpd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzibanev.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtqmgpotip.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtufoplwqi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtcrbwqhgl.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxrflxio.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtiaibgjdo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtjqwcukux.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdukfqjoj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gteidsfcmf.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtsgxpolya.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtghuttsym.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gtvyedobtd.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtfylqanok.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtxwuccinn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswpdovai.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtcwvcbecr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtyecwkarf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtvzwfefnx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtaqdvitrr.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtaoamtgqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtduuhjqft.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjhresfal.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbycofkdh.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtpisfygun.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzmibcasq.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtfzbwmuie.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gtgiyivvnr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtzzlgxpts.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtfadctxsp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbtsjmwj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtfuqmjdar.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtosimanmk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtbhiqlsxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gthmemedwz.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtrelhwqih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtuvikwwga.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtuhbaazbv.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtustihfyj.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtjzamazkc.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtkclrqvly.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtrnmwvsse.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gttaxmlfmb.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtysbqqjoe.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtcuzsiqds.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtugznkoux.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gthsjzicbn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttbkecpf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtpeezgctz.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtytibobnm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gthvkdyvvr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvfclnnz.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtrtnwdwgo.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtcvrphwzh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtcrpzxiqh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtbcoonjlz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtwjbrwljp.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtgpeglhtx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gtamafsdck.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtonzedutm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtwzukuhfc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtmedbxgid.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gttlswiols.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtjmspgzdl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtgnfycivi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtwtlcdlnn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtvhniaahx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gthucdvjqe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtpuvporzg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtpjwrejsq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtxarucpoe.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtyvxwtqne.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtoyzalguj.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtdajwofwe.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtacahezqs.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtilsklkua.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gttutidvty.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwzykghe.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtcevenxhy.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtnogvpgvg.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtmobrcpub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmragwegh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraumjgnp.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtetrjcvjb.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtlkenmaka.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtzrwispgo.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtcaafmhzh.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtkkdvwwhd.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtfsicfosc.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnkwkorn.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtjoarkfht.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtnreffjjb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtmismizag.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtyhrnqirt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtvniqkkvp.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcfnskrl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzdkuwls.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgjncopy.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtiyymubjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtmozjluhu.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtrkhexffb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtkiuggxow.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gttbktvqep.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtgzrynnsn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtaejxovhd.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtkpjlnnro.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gttnzuxsvu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtsoakudav.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtdddymltg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtsdoztdce.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtaywzrhqo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtlwysmofg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gttakfppta.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gttgysplkd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gttzhuyrkl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtvpgsbfjv.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtryafmjgs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtvanlvxcn.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuqprotnh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtlelzduzg.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtrewpgqie.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtnavarxwp.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhhptngx.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtsphvscup.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtfawcbwhu.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtqbdqfgut.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtdmuoxzgg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtfooyigas.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtqjvtauln.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtbbgfubho.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtbwfkebuk.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtookgmavl.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtntsbbzdh.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtbkobyurf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtgvutjxwu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjzogjrm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtpivgkuup.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtbopqwxry.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtcfkvbgpn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtpzlbdvin.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtecqvdhwi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtujfykrbj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtenaavmot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtempbzmzu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtypmulgns.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtstvblacx.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gthbsmppwv.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtjwmfmeqb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtrizwzwnu.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtyaymdmvb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtuebpdrim.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtpeifioyl.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gthhamxdhh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtserupnli.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtwtgqepwu.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gteyadydua.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtksmodknz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtnquedvqf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtarlrjrfh.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtxruaigjf.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gteyimguyt.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtmxwttyos.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtwkzhiodt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtotxuadcp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtmmdxwpvh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gteysfwmne.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtnxdjnyus.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtkzvkvvsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtmvakpxxx.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtqvessktx.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtgvfppfgu.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtfadyjgbv.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtjzfbqvlu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtnpfcxaqx.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtllczzcdi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtcxgmbjwq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gthgdjkzke.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtcwjomudh.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtatnqsvkx.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtfcrknisn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gttnztalaa.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcdgobjg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtrhcmwt.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gthigfwfji.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthmbybhru.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtuvekfhpb.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtbudmpsqf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtjbjfhuzc.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtqztmzhje.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsawwenxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtrabszady.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtemgreybc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtnaudmnyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtufzhkyne.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtuajroqqq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtqnfzrbsf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gtgsxugzvo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtffmbpjrt.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtiexbvegs.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtpfjmtmst.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtmnkshucd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtaoujswnx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtxtxixkyt.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gthqmbhyaf.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtvzfaezai.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtzbileslx.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtyhamquxf.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtoolmlsau.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gthwqlqphl.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtgztvdrto.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtpdyssfbg.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtezwmctpz.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtnnrfbxxu.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gthukzovaj.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtspsikquv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtfoxwjqgo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtziknblcg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtkkkkusmn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtqzbzsvcy.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtefnifsqa.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtgdlzuqyu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtozcqqzsi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtuhsvmtdy.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtrfktidsc.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gthefmxgmg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtszfznstz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtfpafhslo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtmpipretn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlziicqzd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtvfynrowb.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtmcbubgph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtepwsfmsd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyogfqjt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gteobambbl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtzgrqccth.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtrqgihftg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtfmsgemiq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtbtpzzfgx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtjnzqznea.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtjtggouce.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtznhygcin.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtdsosxzdx.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtprbhrtrc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtnxlguwjy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtcyxbpmto.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtjlhwzfit.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtlpfdssfx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtslmqgiqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtplktoymw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtuxqywhua.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtoetnilet.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtsxepepfj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtrmanae.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtthqayxof.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gttfwzmkuh.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtcobwwsrc.html


<!-- 参考信息 -->