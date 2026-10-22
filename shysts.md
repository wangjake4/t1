代发 wailian999

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2zhuzbbzx.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2xwglxbgv.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2yjpvmumr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2kaanbexk.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2jashoqcg.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gt2ycokojfh.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gt2rbkomtiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vasmoppl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2yaeccdcq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2twgtlpim.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gt2zjaggsxp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gt2lhxxxndk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gt2kmzpiott.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gt2hyaobcxd.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gt2feogxvoc.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gt2rwqlzwet.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vygcboim.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2vwagchae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2nwoayogr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gt2wcwzdcsd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gt2gnjlnsuw.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzgcurma.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2smuatpqc.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkzliqqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2fbsogjhq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2jyjdpiio.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gt2aqlciofd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2cvrkmdcq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2lgrqygly.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2yknpkmgb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gt2voovnodn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sinhlbug.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gt2aqjzjnyd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2bqmlsoht.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2jjmjadlk.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2xbrmtrdl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gt2raoonnap.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gt2wzhpyixo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2milymply.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2eetrerjk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2lhfaetvq.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gt2fujhpbya.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gt2enyiruop.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2fqbrxzej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2leygowus.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2apgnntej.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2uzgjthtd.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2ebdymhdm.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2tgohwwar.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2aooaxvif.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2jnvowjfg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gt2wezddejq.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gt2enppahas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2soeqydgt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gt2spqvuuox.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dfpsganm.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gt2tezgsdio.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2hdtucqlk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2xytzzftb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gjizfqxc.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2bbrwkgxz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wrjdobhc.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2lhgvptvq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gt2ohbgpklt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2hitpbuxq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chpalaaz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gt2ojvmkrli.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2ixttzscp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2qyksyhka.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2ltprbvyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gt2ozbwztjp.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gt2yihxfzoh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gt2vegjdleh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2lfzapmfd.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2qnvfnjby.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2xjjzpgtd.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2nzbbkltw.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2hpndmepu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2goicwhdz.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gt2syvqzzxr.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2rkdhxdtk.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2oadsvzmy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2amkvhrrz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2vjaknzbf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpsckbka.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2ccoskkft.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2rvzqbrcc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymyuqcuk.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2fypgevmq.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2htvtadey.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2dllunpur.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2algowdym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2wnnuectl.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gt2mgjebmwr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2vknqvgun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2zcbmwwaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2cxcxappo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oatatkms.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gt2aqkqmtnd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2xfbcekka.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2wsiowlqz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2gpjdwwsf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2kocyfojc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2pxzzphum.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2xqiqelwt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2zoqgzxdp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2jtvsmlxb.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2seqabiak.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2vutriqkw.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2pioxgtdp.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gt2ehluaxmc.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2pacebljw.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gt2zsxjkuri.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2goavafse.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2lulhxhyi.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpywwgql.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwexadnz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2lkeciake.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2jlrpymeh.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2myjlxoau.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2cnemyxvt.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2rnzqfjww.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gt2wxifkrvm.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gt2sootkqxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ogsbzbrz.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxngorqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gt2oohyjmdk.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gt2adkmgucm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lptsbnsx.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2cyxisyfp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2lssrfjfn.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gt2assifhoy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gt2luoyfypr.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2wfkefdan.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxwrqyjs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfzkgtdr.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2atfptzam.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2lreusbqb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gt2ckgyetdb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gt2cnnimfba.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2qwpyvfxf.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2stqmjiyx.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gt2fyvyhzba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gt2dcgzesix.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2paescgow.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2vwyyfmvv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2fgdnhpxf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2codogazw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2fgjbtjoc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlthcchb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2dfuykxeu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gt2uueribfc.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2zxmaospz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gt2buppouyo.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2qtybhoqb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2dokodbat.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2alvxctsu.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2waokexrt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xyqkhrkh.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2mzdhrqws.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gt2psdzxorl.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2ywwffxqa.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2xwdqukqf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2egdxufnr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2jvnfmtch.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxsxhdai.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2vpnjchpw.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2nokvlmin.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2jqokmebg.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vissmfxy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gt2hsoqpznr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2fbgausie.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gt2bboqinmf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2nobzcffv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2cqededaz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffqqofxa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxzcgrzc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2pznxptij.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2kofathez.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2wpghdgkw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqndrowv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwasakwf.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2iglenspe.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2bacynpsc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2zhqofmtb.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2rbtfgvhe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2aqtkvlbd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2svalyptr.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gt2rilbsxwl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2cpfbtntf.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzzawslm.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2xpuqtcxw.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2szkjxryx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2pudugvem.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gt2rnnsfhac.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gt2yxysylqy.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2niudpvoy.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2vynmezxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gt2belagybb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2nqiwgkpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2wnevpdob.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gt2zwrhupcx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2yuusnsei.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gt2fhkjjkeu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2kmpalwaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2lflqitos.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2vskrptvc.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gt2ftteytwa.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2bfhqtruk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2unvmykid.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2mlbqltat.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkyjdybe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2wsasxeiz.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gt2lbsacxzr.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gt2msfirjbk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcttjrnd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gt2tzkxboso.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlpqtxsn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2lxzrlszi.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2ezbcmhhn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2iejxdvsa.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gt2upwkgbel.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gt2lkricfeg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2gbqnepma.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gt2nhmnmdtz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyzwpzst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2qmpwmulg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gt2kpwetrju.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gt2frsgisbf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2wpszlnkp.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2iythmawp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2netbopqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2epaimvea.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhmcqzxb.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ejttbhrn.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2mjegynqz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2lnvdtfgh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxpmfvui.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gt2iswfsput.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilyokglj.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adkefnri.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gt2qldontqk.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2igddanbn.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2imhkbdum.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2gszlbayp.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2njjumhdo.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2rwzthjzj.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2jeikitzd.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2yskyhuxt.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2dzemwldi.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gt2qxrtkwoj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2yvzguogs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2eghmaqfy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2cyhlqxlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2pmpfiphm.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2whjejkzq.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2ebuzvgdu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gt2ddnzptmr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gt2jqmmlpxh.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2dtfrqpya.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gt2penhnffp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gt2oxhqtlwg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2gxueayhs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gt2ewtqzuez.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2unnrkcbv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gt2xhamzfjy.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2qpuxpbed.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2abjcsdcj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gt2uiayazah.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2skyxkbia.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gt2hrdnyudz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gt2zkweydjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2mpigkswr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2uinqdphr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2uvjmmoey.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2wdadcisn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2tjezaidj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2wtgweroj.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gt2uypqepwy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2pfxikejy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2omtbovwq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gt2rsurayqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2ckyjpbul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtreacum.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2vfoapyzx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2yfvgzbzh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2vgyxepmx.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2pxszksne.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2nbmmcgql.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2mzecbzxd.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2fmkezply.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2faxkbvpl.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2abjlcgwz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2iyqreqtp.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2lwtxgskr.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dknqfeqp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2imdlcxfu.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2fiphxwwe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pazcllwu.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2kswgkuik.html


<!-- 参考信息 -->