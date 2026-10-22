代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2sdxqwqjs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gt2lmxqmopk.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gt2cwvtcvlr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gt2hhjallti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2zhqmpxkg.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gt2njtpdmbb.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gt2rhlbmjoj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhtzcxkz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2tvitbixo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2iiiqprhn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2hygljegq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2egvipgfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gt2cjcihzfa.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gt2pmivnymp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2bumocjkw.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gt2czdbmapt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2rcmhrutw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2lwqwodoy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dthtggul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2qoupchba.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2zexuzlez.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gt2dyayphdu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2faqxegko.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gt2doeaknbf.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gt2dvmdtzjj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gt2zqexgrjn.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2plugrdvo.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2figtobqw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2xqmubyol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gt2ednwcylu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gt2umfwkegt.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2ndvqttxt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gt2jqkumgyp.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2kiuhkktj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gt2tdiksbcq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2nxpdyvny.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2yornhphh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2xafrgzrw.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2zwgrxovq.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2yelatwzd.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2ieobhakt.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2kdeqrrxz.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gt2bltwnwwu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gt2seyheqxc.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2lzzuepii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2torwazck.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2taqazbbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2rcyftlgj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2anjoddgi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2icnlxgup.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2armvmlnh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgphqzop.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gt2jddbkzmg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiemalcx.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2qufktycz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gt2xwysysxg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2yqtfidbo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2zugelold.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gt2eusatixx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gt2edwfavax.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gt2gipbajno.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2zempuxgc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnexlzp.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gt2lmisszym.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzclucfz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2bxcvvfxc.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2vrxwpech.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2epjaybjn.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2gmotjnmn.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2skwsevvg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpbvlpfp.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2uabtvqhi.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gt2rwvgdgse.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2zpsxmmyr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2sdvxltzv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2ucqqvdfn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2efpsppnj.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2slzjjvrg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2tbfidhrz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2lvdlughj.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2fsixnxuu.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gt2lxnyqlsh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gt2hzuzbttc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2wpvwimdn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2ukfcyseq.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gt2obaokpix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2ohfpnrzz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gt2yqcffroz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2pewkxfyc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2vtlzutfy.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2zgksshve.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2xbnzrqlc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2qoysmyzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtvtfzsk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gt2oftsryfo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gt2ioommgzm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2zrhyhzgw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2qzkfvqzd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2xdakaeky.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2mygrzyoh.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2npshfpkx.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgzertec.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xulycnna.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2enfpgykk.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2ckqgkxmk.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2auvglswu.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2qlxdrhfg.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhrgkucv.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxeonxmk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrakgfiy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2tpgfpmjn.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2hifddjag.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2nrhgrjgq.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2goccuumj.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2tosljizo.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2lpajgmpc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2pbrdmrru.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2afjrzqbj.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2oddocjqv.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hozpjpbp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gt2syekwmxr.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2cclrjjip.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gt2qmtkvtyb.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gt2ftaaejky.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gt2vhyoiszb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2vqngdrqv.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gt2prbtzmqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2lxdielyq.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2dukbtxwg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2alzhrgku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gt2mzskdeam.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2rgduvmzi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grrspjlg.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2ztklosfr.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2bhcsspjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2pxdmkiel.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gt2ghfwmrxu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2sjjklfzo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2gmicuvqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2pbcimvzb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2sxuqyxjd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2afwfbwwk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gt2npwmnaum.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gt2xozareop.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2qsibipym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gt2nyeoyxhd.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2zplxdzjl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2nevqhdzk.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gt2unxeogtp.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gt2cmiezvsp.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gt2fivhnjce.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2mpcrsmfb.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gt2dvxxnrwv.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2yxzdmtaf.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2pmsmhhql.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzoqvgvo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2gotnnnwh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2mkhfhvmk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gt2waxdolib.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2itbizdac.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paaihhvp.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2ddfugnvv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2xudhqnrp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2uejzqmae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2nizccesx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2esmfsfrb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2bbwqyrrr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2mmonjekl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbljyahh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2gbpnakcl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2gxpntxut.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2ebmzdoaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2fnioeaeb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2zufkwxfz.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2ynvirole.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2viggclfy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2ngygiejk.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2nczezaef.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pubarhpd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2coeunkfl.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpivaczn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2bszqyfpt.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jzutjhff.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2bjvugjrc.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2ztidrvot.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gt2kackhupj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gt2jzqgipqj.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2sqzrtuxq.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2yjjdlphj.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gt2tjfxgavv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2mvzutjkx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2tdxmoprb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2blppbyyt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2fpqiudzt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gt2syhswtlc.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gt2hmpbdsur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gt2biderbof.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydoynery.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2ggiqpkts.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewtrpswh.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gt2tdsptreu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2kilgiazn.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gt2nswaifja.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gt2srvjnaad.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ajwyyxdi.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2sqomxvod.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gt2yyjlfrvy.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbswrljd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2epdolckw.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2qjhniydi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gt2phlhdlej.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gt2ownemwbf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2rrjvvalv.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gt2xvcflicr.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gt2mvierkbj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2hrtimrkq.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2vkjeaofn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqmhgdnp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gt2mnyfdwfp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2zlwvhojw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2wazqbguh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2adqzvona.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gt2humpeami.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gt2gqyeraow.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gt2mnuetgsp.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2bwfvunuq.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2afnoqlqb.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2hrwelnda.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lquieuwt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2kzfdxlyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gt2rmhunmtx.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2fjxlsvss.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2oqzlgczt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gt2gzrhqfcy.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbzzdkex.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2vebmybur.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gt2ryymiigx.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ibluejoa.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcgrutnx.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2pzwwganw.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2sbapaioq.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qodegzjc.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2lqldtudx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2egnopycg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bcmyhtyk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fagnsblu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2luhmbpwu.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gt2vfamjbee.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydhqgbsg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdxljosn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gt2vkqmqzhe.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2xecgeixh.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2dwtmpkol.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2weobssmz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2hzuccspp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2ubijsdpg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2uewsftmd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgchwotg.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2rxqxzgkz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2bwmzklng.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2mdpupxiz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2qevwgjmq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2xabzjoxy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gt2zyzaiplq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2titloeza.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyyikpsf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gt2haeoscvb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gt2foslltue.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2ltiuapfo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2kidldbjk.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2ynstfgiq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gt2fulhznau.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2icgmngmh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gt2owmstxet.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktmabott.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2pikwtsvr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2bqdzpyja.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2hozrhtik.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gt2znrqgaoc.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybqhgmnn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gt2rbabcjhp.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2eorfvksx.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoqqwkqk.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2cuelhgll.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2wxzvantk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dexsmspk.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2wvtokgfy.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2faycsbow.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rofvquqo.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2zmkoyrsy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bjqjefgd.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2uyzxzxpd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gt2ylvhnqrf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2amapqggf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2jvdarwse.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2wtsnhsjv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2yhywouyd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2soghszew.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2brlijwqy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2lhhaikts.html


<!-- 参考信息 -->