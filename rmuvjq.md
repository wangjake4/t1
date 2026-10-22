代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2crgfgarz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2ngezquhq.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebemlhzp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2kbsmfkqr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ollddomk.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gt2eeszknpx.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2bansdmxn.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gt2versywwl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2aqsvrylf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2xrxpwamq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2eqeoojfu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2xxltgocb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2ptwjnuxr.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gt2rjblgbgp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qumzrokj.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gt2gwcwhovy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2ujgdcqfq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhvzbohv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2gmvlladx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzarxbau.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2ugyuojvu.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2bcarjosd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gt2bnpafjih.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gt2nfqkgdtu.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gt2rtjhndiz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdsrkell.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2hhvsscbp.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihzwprvg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2suwwkufc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gt2ukrbrore.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gt2opsrblya.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2egfgqvan.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gt2gzruwqbp.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2ghrszvio.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2proseyzh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2orcjqieu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sfknviex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gt2xtcsimwl.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2ddhkzveo.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2rgrmbnzw.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gt2tqbxyfdw.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnxlutfo.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2kwsiwwzd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gt2fntthkuv.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gt2owenfewi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gt2lbhsnznx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gt2qhuhcadb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wrzefwda.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2tptmtcvc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gt2fxmuoovq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgniuijz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2opemvjkm.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2rjqnuvjh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jmymyvvf.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2ivwjzwkc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gt2ykjcazob.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2ifnjbazs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2nagcnrtw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2ouvwjbgh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2rsolsfzn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2erscbhdt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gt2pjznqayp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruedxqhz.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2ewjdmhwv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2wnfugogr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gt2gyqytebg.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2qzsixzkq.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2waucsdim.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbkogdbf.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2qvlkpqlt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gt2jhlxzfzn.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkzbmeji.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gt2vhsuzflf.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2mxkpynup.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gt2qvpvytwb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2guarhwun.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2vekbnkai.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gt2ewnehwus.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2cowulgdu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gt2naimumaq.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2yfihzqiv.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2xpltuezh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gt2ofkhgryy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2owsxyjnr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gt2zhmcwkki.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2gwkooiic.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gt2omkkcifd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2zkqwyhqk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gt2uxvknweo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrjdxjbs.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2cdsbtgvo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2bvetqhxd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2okwwhhhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2vgxidsjm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2mgjrtfei.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gt2vlhxzfmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2gtsqdpvl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2uztwdqns.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2ckswpufd.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2rsdrmsjg.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2gmzfmhxu.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2cieutyzh.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izolwamv.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gt2mvburihm.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gt2wzjqppzv.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2vzzyhrez.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xljlyghl.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2aptxokuf.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gt2nryjhkke.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gt2devlztej.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2lojgshrs.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2ueqrjjqn.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyvcmrcv.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2wocctjss.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gt2bjdfjsfv.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2xdwmvczr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ivpaoazo.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gt2ryjfbhvk.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gt2hxdwvqcj.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gt2fkwcsepu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2gcoavahx.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gt2aflgykjq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2vjmkljym.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2gwrooxaa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2kumonfjb.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2mikionxx.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2efkppskq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2pxadaqky.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2zmwybotw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2uudwqmvt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gt2aqelmpiw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjzjrhre.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2frvevycn.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2yhpabewc.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2pfdojzul.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2bktiacjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2tfkoxfqt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2rxcslcmh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2orkhmfsx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2fexyvilu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gt2gqyuktvl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2vubapghm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gt2umhayrif.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gt2wfpqehao.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2twwkbctp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gt2boxjshhk.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2kcmbmstf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddnlgqeq.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2wdcdalic.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gt2sloggywh.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvfkdzvc.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2zlqlezke.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2tzpqiryw.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2rqegmwlz.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2ddtctacp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2adlozoxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2vzlfomtl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2kcvjuomm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gt2gocvqknp.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2uegzvliy.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gt2lkyhrsub.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2wsnvcorm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2cetepetf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2bnkllnws.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2lktscjpt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2djursufo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2ghqgxhxc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzypwhsg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2keqqpttx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gt2asjvupqm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2uoleuhhb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gt2qcjbmxlx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2mwrksdia.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2vacczito.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2czivkcet.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2xtbaavgi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gt2apdbdcsh.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2tsmrzcfn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zodnnfss.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2tekbiauf.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2zgfpnzzj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gt2lgnqaqid.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ozhylkmd.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2ezymguml.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2ppjgduxb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gt2mwwccarw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2ixnjlzuo.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2bxqxjrwl.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gt2bbvgiain.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gt2fqpuzpgu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2siyimtju.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2sdhsgjqo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2utzxscea.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2inaumeay.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivnrvqmr.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gt2zzpfspvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gt2vcmrwfcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gt2bjkpbler.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2cchsculj.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2fqfdjkpb.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gt2dtfmnhnm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2eorpmgyz.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2cehizafy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gt2ampqjpoa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ptwxyjnu.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gt2ugcsgtfp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmkgpdam.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwckgtmd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2kgftcikh.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2izfzgyfq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzzdultz.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2thafecqg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdejhmkf.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gt2yfpswjcy.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gt2nneshuxt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2tpgsthju.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbbdllue.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2zkedsplt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znabqwbx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2hiucjaot.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2wryzrdfc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gt2jpgfiwvq.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2okwudflv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2ukfvrvcw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyynrvyn.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2phndsnmj.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coltzxtk.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2kcruoltf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2mkbkotfp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2jjhbpeqo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gt2cbtlimqa.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzowyiq.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gt2zffxoaaa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2rzhfliod.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2frvmuonl.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2xyxxygbx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gt2imuqlrgb.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tghtmqjx.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2zraxmiff.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2peiplera.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2edzlisxf.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2urmzwhtx.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2mhjfwbeo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2suaclaeh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2bsggbmbw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gt2eamflsht.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2dwzkppfq.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2aslmeegc.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2rboivndq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2ekruhjdh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2ortfgdnx.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2imazrbok.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2vczfmbsq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gt2adolvowm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2shdztcjy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldmgxdf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2pkjqjiic.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gt2tivxwqiy.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2xsczbsqx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvmkgbqf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttlhzfow.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2flkpohyn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2oncqmxbh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gt2diwpswem.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2gnoousjo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ybwvkcld.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gt2keygpnfj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frwjrblk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvfdcuat.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2cvdqubmj.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2ifsevbdi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbarkfwb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2kmncdoqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gt2lccfvmya.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gt2fluenaxe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aenerqrx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gt2mlmkagvz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvlwbdvf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2wymwpczw.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2ihldxdxn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avqgmvvp.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2cvtqufqz.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2udqbnclz.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2eqkfxuox.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2fideemxk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gt2fqfvauts.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaeeyogi.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2nmjdzhoa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hbxtuoxr.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfznqhtq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2dklhymfs.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2uonkohrk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gt2aojpnobl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2msmzuxuw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mukncojp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2byukzrgm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2vnypzwlr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2zzxfhkdf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2rylytzdh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2echgxrcm.html


<!-- 参考信息 -->