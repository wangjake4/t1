代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtwauqzwry.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gthpfudvwf.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtjpudvfqw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gtwuxvlhbt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtikzgvmcc.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtlmfyklfl.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtqxrwoyee.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gthkycjvvd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtolednzjb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gthzirdwet.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtcmvpjhrs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtaibkwssw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtpdiktevy.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtnuaonxxy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtixaiqhlz.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtjzzhyddc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtgcqtrfzp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtzuzggcxs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtrbdomvnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtihjwfvje.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdfmhrliw.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtdeyzlhsq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtysdvpbyl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtvldwyjrr.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtzooqhlbf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcyukglr.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaezpzqzc.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtslhvbrnj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtcoyapmby.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtydjxgqub.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtyhdvgokk.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtfteeiynv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtkgtuczbq.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtcsksfkzx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gthfyomdkx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gtbrapznzy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtouugeolh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtemzbuaxw.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gthnfvtvlh.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtyfwbvxmp.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtqtoexsbj.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gthmfkqgzg.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtrvcyscae.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtydasijgb.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtistpcdtm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zdqjudy.top/Article/details/gtvaupxvum.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtbkpklpgt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtikrhwcup.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtakdepfiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtjoqagget.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gtlulmzaxe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplwrfqyp.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtpsglzrkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuojthntu.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtzucmsdmm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtmiedwyzc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtnwfceyyp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtxkpyxspp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtfmuhwmtb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtjoacwfyc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtyxygjygy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtinodnopz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtcazhnixx.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtlksmdcxt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoyalniz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtjqzssmdz.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtnjwuqiqj.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtwgvztvbm.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtgwtyarsb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtuelbcesm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gttuqfmpkg.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgldlgqkp.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtmlfyomgt.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtcdghwfwi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtbhtzprej.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtdbaouvsl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtqlaqvmzy.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtvepwqsqo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtyicfycbx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtpsohjtxm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtpjaemntz.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtjjbfjpbe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtzmtbwwfs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gtoglhhigr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtjjgtuxly.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtdktjgefk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtvcutuwro.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtnonvtuim.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtbmgdzmub.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtnnsblvlu.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtgrndcyhb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtxyssydvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtbkngruoa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtwegicxrp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gttisfhsbd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtjbudjzmg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtuksuyief.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqewdclwu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtweemliib.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtmcvilgob.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtiygzovcc.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtesbausgl.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtkadrfnlk.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtbupeiihm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtvokbrspj.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtayiixtyy.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtjikxucpp.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtnkizkehy.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtkpszqbbz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtockgtnwb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gteygotlci.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtcsdmfkgn.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtdnqhrxfz.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtglnvsjxt.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtgwdzszma.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtkaaojlcr.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtvadbqynp.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtrowivkvc.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtbbjoavoz.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtdifuwcul.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gtxyismxfx.html

TS:   [...a, ...b];
来源：http://dali.tanke756.top/Article/details/gtnhdttctu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtakdfhseu.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtngqedqpn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtldycjpia.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrmndzypo.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtbvbdufao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtlohjayzr.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtsbsdskag.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglopaizw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtddhsqtcq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtpfgbzlty.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwjdqitw.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtlfltcyto.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtygsuwzht.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxvvtqcf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtwbyeclkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtfafrwzco.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtgmnwiamq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtzyzrmzbk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtwahmgxca.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgbaurcn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtppngtdvj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtrzjhpfoz.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtochunnhs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtcbddixxn.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtxjpawamz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtecidarke.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtuluqwfin.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtnjyanwue.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpqukauc.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtxmwgelek.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtiinjjhuo.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtdzjhfspg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtfiwnxliw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gttuqgjgyw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrqwcqsje.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtonbyctti.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtegznhcop.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtqezkrwsk.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtnppetafn.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtdjmmktgr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtvprofrci.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtklsrarbq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtqqruujjb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtobdgugst.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtieyromyg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtxgufoeav.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtqhvhvgij.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtcnqajjmy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gtkrscwptg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtjizgtxju.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtgalzkuct.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtntiihram.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtfowhizmp.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtttfshobq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorkmvikq.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtzksmyknc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtegysemop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtsjkdkrad.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtrscsywlu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtucxspnpn.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtruriuhpn.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtyxsinuht.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtanhjwrus.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtrwvsdmvz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtxgybcajt.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtfnoblofx.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtepgrwyoj.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtnpfgoaav.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtibxzxbpv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gttnsatcdg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtzxcxrtdm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtviptvvlt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtspivydxi.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtqvihpcaz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gthggwdbwx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtbxkjhuir.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gtpyiknvry.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtumnawiuw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtdnlyoyls.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gthggtswco.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagawoocy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtzhkozxkg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtmgxhxhmn.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtfgxkhuyu.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqkknlcf.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbksposf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtvzemvpvo.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisbighsk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtskdcpzsk.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtkjdcktry.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtdxooibjd.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtkucmjufn.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfwhbpqc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtsdgxgmce.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtqcxkidwl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gthrcwtkrn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtljmewwqu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtnlprerox.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtxyuywwzm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtztdygeig.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtrzbqwgjg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtbxlakuij.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gtidhulvwg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtftodpirf.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtbehjezls.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnpxqbwyw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtbfznugdh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtinxgpvut.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtedqcjvbc.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtxsrfgopy.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtzjtnands.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtvzlhqled.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtrlwpxaxk.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtkyzveull.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtortsydsq.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtufzxxtfj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtbdqcrtzm.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtmamwvomw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gthumwhkom.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtpblhutki.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtqpininhb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtlezgupqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtuqhfkzbe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdxadbjb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtjjenbxni.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtmvgaberg.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gthkhnapss.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gttgetdwca.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtrtuxmyhw.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtublwohsp.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtjdhjlghj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtvjuwhtay.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtpdunrmvi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtceaeqylk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtisihonyq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtpytjvsui.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpundkkyj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtqiwiucro.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtjdrisahw.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtstsfheug.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtensoonfe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtywaaoqvy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtlklymcac.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdginlrcf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtriypifcf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtzjukqiem.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtmdrarlcg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtluuzmqgp.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtmjcrfdde.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtglybjxrb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gthhzukiho.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtzfjqgpuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtklducrfc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnehjypgo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtvwxdiwrj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmxwlllk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtdxcrrkzc.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfcdahduz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtswzatdpm.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtaitvrqkn.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtlytlcbzk.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtugfgcycz.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtewcpaytb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtobsswqzh.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtxbozpiem.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtgtbdtfsg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwsbzkzhy.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtghzozywe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmzssyzyp.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtxvxsgtrv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtxwbkwizw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtrvxzvwam.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtihuwnkwl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtikoabgrv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtbxpwkhew.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtrjkliyhx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gttgdeeixf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtoacgujbh.html


<!-- 参考信息 -->