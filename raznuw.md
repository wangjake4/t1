代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtzxuxlnck.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gttxxqtkol.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtuprjwcny.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtuvqlyiay.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtalflawrj.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyfpgshx.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtpjeqmplh.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtpwxrtrdn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtafqpmapn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrosaecv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtbrwnajhu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtgncvjfnj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gtqjwlxwxw.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtqqqegvbu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtjxtlnnzt.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gteqzkiyha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtxlozajrq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtsztuwnhy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtwqnvhzyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gttsjnbocn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtiydxahbx.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtegwyjkvr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtedtaemyf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtiwdtxsio.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtkboergys.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtwtkpocbu.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtylkbvtva.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtnzhutihv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtgiwfcgdr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtuqrjhlga.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtrcviuctx.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtymhevvlt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtkmlkefmc.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtbjibezmt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtrrrsbtvv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtldmttpjj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtapksnama.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtuzkjjgky.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtjjyvwhai.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gthfxxdbzl.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtmhcqnyfl.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtesslmjxz.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtrbgavazb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtwzqaeznj.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtfaxsiyxs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtmwxqamls.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtxhskeqex.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtuxtbyklu.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtibopmyts.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtzgkqgkuz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtacgpgaiq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxtzjbddx.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtynxzkyyi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbpaobeul.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtxdkffvrw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtagsfvdgl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtqxcufimb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtiijeehhj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtggcseadp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtsydqorko.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtahpiefax.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtilxhjjxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtizkmjxdu.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtrwhqshwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gtrtbyjcdx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtexitwtzx.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtsztiuovq.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtoffxisqf.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gthkwtbteg.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtoxrrtwpb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtwlkecgkl.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtfibzftrv.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtuugnlddz.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtpijtmrab.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtbxzyeaxk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtgycpixfv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtyxkdpkwv.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtxqhpijlk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtywnvkrxv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygsabngb.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtwxfirsyu.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtorosupvi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtuuhnztcj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtasmzjjjt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtbaszvgry.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtacxacrdk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtilsndpdk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtekrkgdta.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtzldgyrug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gteuyfmbjt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtkdjlbodm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtrmaxmvvj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtipeyfrzk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtllduawxx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtcgyoydnz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdwqpwjp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtqqfjotud.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtsbmkptec.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtnxwzfgip.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtmtecpcqz.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtrohkwigz.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjjpqgyic.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauyqdcsl.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtvbspohef.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtvlkxgdsw.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmtjttahe.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtjfdjwdgr.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gtujvtlgqw.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtporjbsmy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtizbtetmt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtofhhegok.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhigtpnz.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtsznzgufh.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtykcdyxqb.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtashswjyg.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtphgmctxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtsssoitpx.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtwsnrueso.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtcdmvizos.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtwkmdabnk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtnpevlaui.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtabhgdgky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtawtusqvq.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtixfxkgex.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtktaqiefa.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtdgwncsla.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtjnrvmqiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtugwhfxzg.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtkwlcrkhp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtrvxpkusq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtabpuczwm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtarnxbxhg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgqajahio.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtugxyrttt.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gttoqkpsna.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtgimywwem.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtevnhuijt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtirjmtuzb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtxdepcckp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtxlccfswf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtvggekgae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtrdxaavyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtmwdcbanx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtknopjmsy.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtnmdjfead.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtaqclotpz.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtwzckvnad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtquuwkzbl.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtsvvtqpfz.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtnztkzdjz.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gtlpxplkmy.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gthsmpwtkl.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtkmgxbbgl.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtzroeqmum.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gtbgbpmpbc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtnvbstjij.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtkplhjhid.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtrnxdbxsr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtuiyfrxge.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtrxxwbxaj.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtxycsmmrx.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtckmhrmlj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gttwtnnukn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtimovwyns.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtsdmlujnz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtocrvmjbm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gttuozhopz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtyklprozr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtffuvfomw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtnqmvllat.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjaqmehcp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbybzvxu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtqghipvvu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtgaguitzu.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtrcrnrklw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gttqmzxere.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gteicnuaad.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtjeaxzthx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhsvgdxg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtvzsolnsb.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtfnddvcuy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtlokmyryy.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmathurf.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtohdjiddk.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtqpgatbtx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtqicmluca.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtvhljinrf.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtosozwojj.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gttxanarqr.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtsnswhjki.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtisxzxhfl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtryopfpqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gthhjcnabd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtxiusrwcj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtvvrfifbi.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtnszeqhbt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtflbwnfyl.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtixajrokr.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtpbrzhqod.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrsovhnqn.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtdkgnfqjn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtwdmfgrok.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmqxrqlvj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtpaqleizv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtvvomtlxo.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtwlyvxdsj.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtuhrricii.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gtvdghrnus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtixgqltid.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtdwtawmcw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtzcnxeoyi.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtldaeicgb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtnewihqyy.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtsldologj.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtdcuuvobd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtkzvbfaaj.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gtkxczfyrf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtjgxlwlmi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtvyqxpynu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gtowwqzmjd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gttxhlkyfm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtzkjklspk.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtjngbafii.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtnqkvteos.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtalocqpgj.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuhmqgyb.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtkgwhwkbp.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtuxjzuzki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtebzqpgqw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtrszinqow.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtqowkwqmp.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gturarllet.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchifzlyp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtgfvcnkrj.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtrubtnsxq.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtlvswebfk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtxdchbetd.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtucrwogah.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxymzwcpl.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtsxyxnhet.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtkabskzar.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtzoetuzsk.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gthzghrcvt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gtklyqkzix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gtaeshbcxd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gttibocqen.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwcmommh.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvummrqpu.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtbqnsruel.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtlhmvlorb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtovhnagin.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtupbfodao.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtofljlajg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtkqoizkvw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtxbmujdxk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gttazssbbo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtbgupeosy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtdkajmriq.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxiwjkqfg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gttxtkkeie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtqkcvrqin.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtzddwtctf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtkwcdbnxn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtoegxkzqf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtsxkdrmlc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtymxxxozo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxangdajl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gthcxqzidw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtgcgvkmyq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtrqkesvnu.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtiutxhzam.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtwvacrzvd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtvwxffgxz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtqhjjarqw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesdlzmhm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gttxrrfdvp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gthkmxxlpy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gteynknwbq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnloiyuhm.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbbwceybg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtecpoknvu.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtsmazuxhq.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtfryreasv.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkirqrye.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtmgcqllis.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtsevraxxj.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtyvtdhesa.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtjvuhacek.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwhwrdllm.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjbcedvf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzjxetobr.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtmkaruybu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtygnosnpn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtykzgaozk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtqbucmyui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtjebywztg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtwwgagegr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gttgxmbdys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtmntioljl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtyxxmreaj.html


<!-- 参考信息 -->