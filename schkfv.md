代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ukbtaqjn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2ckoaiujq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2tldmffbv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqzxwnzr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2whhqfrhx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2oiigadgx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2dxdswioc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gt2kxjhyduc.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2qbhmpkav.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gt2kadgimsc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gt2qipzietn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ixjwqrvt.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gt2lvxgwpzn.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2tivcpeoh.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2rmtnvluf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gt2lmcqaafr.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2svumldzj.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2cktkdhsp.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gt2hvhltbvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2vbddpjxr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2uvrzsdsh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gt2shtxohlk.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gt2giytoaci.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gt2qwkqvnnk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2jaktgddy.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2gnirwhjf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gt2naszvmli.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2yaqfgpzn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldokvxct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gt2hgcfmxwb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2vhvuyhmv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2vnnlrxet.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gt2kgynwbfx.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2naaqdtjm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gt2tunshqfy.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gt2lxujbole.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2iprtlhtt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2nruoqeti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2cshrsmol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2wbqbmosi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2fvpserjr.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2rkjsrrat.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gt2izedenml.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gt2krwiqyfe.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2uxbhdaaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrjibcci.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2lgaovesv.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2lztpltak.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gt2qnyvqiwi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gt2czgijrzk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gt2sorvscjq.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2pdmdtqcr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gt2rtsxhbud.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2lbglpwtj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2idptlnqm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqvuhcmy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yqchvxcm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2oaqvheax.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2awhokeat.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2facsgnpf.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2wvrzgbez.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2yowqopkc.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2okqltbpr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2tppnhepr.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gt2gkzctjek.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gt2pccfhkek.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gt2cfvzivkl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2mcgxocuy.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2kyhznlwi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gt2kmuhdbjz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2lduvpsod.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2powxdmkc.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqsxtgei.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2foflslda.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2rmydnmqa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gt2xnxqfvtk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2jimentsk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czcbjfvc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2gssvcfvu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2qbgxirgn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hytukymv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2itutjhpd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gt2trtdhjbw.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gt2gcdehglh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2mlxgknss.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2tmgnmqyd.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gt2lrjxeqpx.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2uudlbiyx.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2piltyugf.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2jkbfwzqz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gt2qdcfmvoe.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2uopoexxn.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gt2qoqukabo.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2dyhyqnwz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2byxtdyvm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gt2ysrtvihp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpwouldl.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2ekwepugd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epfxptxu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2aocroytp.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2zahamkgu.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gt2emhhtxpv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gt2hcxujdbq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wplontxg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2vsklutlm.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2udufedwl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtwkcieu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gt2bktzddea.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gt2hzsvxtgd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gt2gnmglake.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zerlzowo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmyaliye.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2odwywfby.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2cizpnyqx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gt2znvloblo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gt2ugbpgoah.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnibfjgw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xujcxntc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2jcuiqkjn.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2fvnjhptn.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2bkobsiaa.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2abqvwhxt.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2ynbqtglh.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2bfgxyulh.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gt2zdklaoad.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sadsfuwe.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gt2ziuclkwj.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2fulpjlmb.html

[D07] 切片 / 取子数组
来源：http://dali.nwbrower.top/Article/details/gt2txzhnkbt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2serechoy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2kdxjoezb.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbylgfpv.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgoklcml.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymhoxvvk.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2wdvuzwvh.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gt2erfsmzqv.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2jattvrsz.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2fqykyqwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2uyoxeqdq.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2zxzxwwmq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2nqoufnya.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2cdbusxbi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2rlyocqkm.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gt2gtvvsyqc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktqtwdxg.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2gkwiujnw.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2pbrjiifl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2smflousb.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2byupwyoi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2ewuseslg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gt2whthzhpj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2blaqnifo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2kpjygqaa.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2xcgurngd.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2huwdxsra.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gt2nflpiciu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpruzkzt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpodqwsz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygrpkqps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grmfzpdh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2cvkraxhf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gt2gtotbbtc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2xajbeavl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2bcbeknua.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2abktirfy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2motgttzd.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2izbqlzzf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2pjfxqsoc.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gt2pevqexrm.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2kifidudp.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpxdijms.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2hsjzgbid.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2togdbbev.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buwmgboo.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2nnprqpde.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2badpiswj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2ocvvolpa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2irvxbhpj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gt2ggeqgric.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2kxjogexs.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gt2jatzxqrf.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gt2ubbwbqgm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2otpryody.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2mgkgltgw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2jnimepzt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2hbfbnyvy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2pillumgd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2icxzapmk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gt2ifenbeqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gt2jnniyetz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2izrsibki.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2vasvjlad.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2copnudlw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2wmzsuzac.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bvlmulhn.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2qeppmrvz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2yiidllko.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2fkplxlsn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2nfnigpae.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2mzfjgute.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2piwzbobn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2oqbliepa.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gt2osqzpuck.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsaobjqi.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2qwhfzhks.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2ogewpcwt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2nscjnded.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2wzgnhzoj.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2sjhoolxs.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2hjpikvea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2zmyonwwe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wcymtqoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2dmfsiwqp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2vjuzisbi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2idtoncqq.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2glvajwae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqqyabry.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2ajfwgmul.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2htqmszpr.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2pszlyuoh.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gt2trdeowda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2lxlafaim.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bblksbtd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gt2dcojxgkn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2dxdkncet.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyuxtoiu.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gt2szazrqum.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gt2njtrchvp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gt2kmrbblpc.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gt2tmplchmk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gt2cbmxxjnp.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqeywscm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2nlubllth.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gt2tytcwznn.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2cgljybng.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2frixkplg.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2pcwynzvf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2zhxfadkj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2yugvcghk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2excjyevt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2xgyqghkm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2oeotdeiv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyjcpna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2tkoejgwz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2kaeiyads.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2pkorqxem.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2pbqlctxk.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocrcexou.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2zkpmtggv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2qnqhzxbn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2mbdyefhk.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovvimxna.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2yxbpifih.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2cbakupfx.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2czthlhlw.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwlrwpnz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gt2zdwccnlj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zekdtwvn.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2lgarwcir.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2whtmbsrz.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2slzgabdo.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2sawnhfzt.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2kubyiwhp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2guacrvdt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2vewtzfsk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxknbxfj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2cfikxhvq.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gt2nhytxuwr.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gt2dvyqiwsu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gt2yfvpbfwg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyhkgkxc.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oexjnnqo.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gt2glxuqodk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2tuqqweil.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2fbobneiy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2zalcrrxr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yryihlaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gt2pzullfhk.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2risweyul.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gt2kyxhujcj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gt2ovdrrlyh.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2lulquggk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2otwnyucu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2bbcugceq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fcvlcthy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrsjwglf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2dgdhyykp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gt2jzdnrqjd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2naykrftp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2pkfiakam.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2fqalcjpg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2xodunmyp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2cyrcqcom.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2jlifezgm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2ejfuurou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2squroyjr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gt2pnbafbcm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2lpcvbjjc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gt2qxiuopda.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2zvpekcgd.html


<!-- 参考信息 -->