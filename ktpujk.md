代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2wsypwaow.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2uanfifos.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gt2waudcbrr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2cooyjaef.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2qlstrbxz.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2csvcpnhn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gt2lsjsmesh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2dsuvdmsw.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gt2lxtvogwh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uudypjqo.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2znooareq.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2uwjebzoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtgnnjaa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slzxrzid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndvhqwao.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2iidngeyl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gt2kufqqsmx.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdzvpzjz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nixqdpqy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2icgeipro.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jjlrxots.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2wrwwzbpv.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2ggompvcg.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gt2lvnjjhaj.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2jqiwomlj.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2yeaskxpu.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2hmyuyeal.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2ydmohnkw.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gt2urdzsrfe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gt2qdomorbe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djhgnrdn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vmzdijgj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gt2oghmcemp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gt2mnbfzmfk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gt2uxklvlst.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dtsrhqfi.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gt2bumfqqls.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vyoebatr.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swlzyhqa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gt2ejgohucf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2apffugcs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jupuglmd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2minmzhvk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2dxiuoykl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2kprxurmp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2nyealdxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gt2nydfzpjb.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2nldjcoyz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2gtipzviw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2amtnbdwg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srqvwzwd.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2nalwhsat.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2rgnhonma.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zavkuwwu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gt2mfbiqcxi.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drcfdmgc.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2nexomfti.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwmvtumn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2rjxaafqi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gt2gidvvpye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2xgnfzofa.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2anipcout.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2dedkabou.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2iogpfoen.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2hsxdxlga.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2nprftyhl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2mmbtefgq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2gvbxoodf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2ybmewchx.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2petflviu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gt2dzlycgqk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gt2zrjlbvta.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2xyujmabb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gt2yppykqqk.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gt2ghadjqbg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtaoylpy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2crtsnofg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2nnpyeksj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2dddilkwz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2rrfbbhgj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2eudtssob.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwhpltiu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idamypwm.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2ofzeqsml.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2viqoywig.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2qkakcoag.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2tdsgzfgw.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhpycjns.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gt2jkoiurmw.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2vrlxmhpt.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2cwbddfya.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gt2xebhlekl.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gt2ttfgyyyd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2cwmllmya.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2bdivgmrb.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2pnemgomn.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2atbpvwie.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2sjgmzofh.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfufxfux.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2hbrkysew.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2godqkvuy.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2owhgxuvg.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2teyyrrgh.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flrcrold.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2pudvxfzs.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gt2fscmwpol.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gznohlwx.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2wrodbqax.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndlpiqhd.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gt2xaavrywq.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2jjmlggmf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2jvlqfgeb.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onwxyxhw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gt2iqpufxcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2vktokreh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2lpussfvt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2grohxfip.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2pmkvufup.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2cmpmwrfs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gt2nzbmqihc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smxzzucy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2cydwqkxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2unbnoftq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2hdfwlgdr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfugtjj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gt2fzyzfost.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2ryjzbhxg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioripnde.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2typccldo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2dqgzavog.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2elpznroc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gt2dcyyihan.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2pbbqrdac.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gt2emdoolsb.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2tljztqpa.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2kdtnveao.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2ueyqgsha.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2yiqosywd.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2atxxmduj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2gaoptclj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2chpblbav.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2uptbmoge.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2myxjytja.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgzfrjde.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gt2bomyofuf.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2wovehgcb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2rjgetztc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2ilouyjrh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkvoidlp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2fzzruwzf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2vzfzjsxv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gt2xnauvpse.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2vewdsrbh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gt2hdvpdktu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2ydgtyuie.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gt2dowjvjte.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2jotfyfmk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2vhhxidmh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2rzvgiwig.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nstmbiye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gt2ixpxdfyq.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2qboytutk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2felivthx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2dzadoosd.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2yfuthphg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2lyiogzxf.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2dhsmbrpa.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vllnolqy.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2cdnbgdey.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2pgrzrnqo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gt2qszyexyz.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gt2fnyjaeaq.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2ubtquoxe.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gt2dinrlqya.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ckwjdoim.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2eyjiekdk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2yablhddf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2kmhbmcbr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfejkkms.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2jvwcvpmb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2gyygfjcf.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2mlkrcwgw.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2nghlxlaj.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2otzefbmi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2zlgrjdru.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gt2jhfvdpyl.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2yqsnxccp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdaulfwh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2qeaxyfop.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gt2onxctnhp.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gt2sjiugusi.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2yzvctqfy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2pehmxoyb.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2jgcgipnl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gt2xktzlgya.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2salofrli.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2tgbpgtio.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gt2rvstvekc.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gt2wbowelur.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2hwnkqmfk.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gt2ufpqpnoo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gt2daqzkykq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2xnuvyihg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjapnkll.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzerbruy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gt2xsizsmkw.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gt2ypyowpmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gt2vtshmmgo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2fmqvtoxx.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gt2hzneqrqx.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2smploavv.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2krqqlbgp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gt2bhrppgqw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2qwpzcvqu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gt2qoldnidz.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2npmgtlpt.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2jaufjwam.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gt2semvpumm.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gt2ewjxmqyp.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2fnheavrt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gt2uqvyazxh.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2gfodmeiz.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2vkfubbgm.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2wrjiylqq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2feazsjjy.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2rksjtdfo.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2tuqxxkem.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsmnbzjr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2rvhcrpqa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2siozzxyy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2atqhfxig.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2ysnztyxy.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpqxvqwz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2bwircuzt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gt2ltxqtvmh.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2qqyxhvvx.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gt2jofrrlki.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2nrlhmbrf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gt2ggpxpxln.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2emlncsoj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2vuxpbtqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2sdngnpyg.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwnqpran.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2fatuuwxs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ecggzqxx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2lxhwfvca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qujmquva.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2bahuxxxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2awcqfagd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2xjdhtnfc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2eiutaojp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gt2xwbaqhaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2hmjdncfn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqvqredo.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2mkjzftzt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gt2xwkjsbas.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2mykvedtn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gt2astauhsf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2ndedjbul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2wvzxxfao.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfpirvzl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2vsrlecmp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddciwnbo.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzcfavtv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2thsottxf.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2wkfelrue.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2pohpbgth.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2hyebtkyi.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2tkfauzsq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgindcis.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iezqrgei.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2nodcigzw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xdxswwmu.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2nvyalaaj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2oxclopxq.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ozfcbhbt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2ppscoyhe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gt2dusbpjht.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnmureqi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbxpwsdp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2ktowtbzp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2atzzerqo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2lgpoomfc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2odosalgl.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2zfpbbnyx.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2enkockfe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gt2osgpmqre.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2ahxycllo.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2rcagmjcn.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybkgtjfj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gt2aqiyjqmk.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2lmwlgmqx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbfdhvhc.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2rllfsewv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2movsqmmb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2gbrngren.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2tnzcjuwp.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2qrztgbrp.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2zqvpfoxp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2erfxmzov.html


<!-- 参考信息 -->