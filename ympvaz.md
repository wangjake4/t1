代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdfkqhqh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2lbdedyiy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2hiqkphav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2hqepebsv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2mkeovxfq.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gt2mudesofe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gt2sbplxilq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2cfjyaafg.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gt2bmsfzkba.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2idjugltx.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2tzokgqjr.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2cdpfmkfh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siokhzdo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gt2xxepwozg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2undlnbeu.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gt2pfhgrhji.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2jwwfftlt.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gt2pbuqdonc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2rncumggs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gt2ivsjfnxp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2blfcjwnb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mhbledaz.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gt2saqapqzw.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2awywyupp.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2xkzqrmep.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gt2deuhjmtj.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2zkjrsnnp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2limewrfq.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gt2deedtrgn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gt2raufdies.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxrkvvge.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2caocinnm.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2dmrklhkq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gt2blmaazed.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gt2zuszkgux.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bccrxybh.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2fjybqbmu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2rkybddmy.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2aoupucqw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2ioputdrg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2oepqazez.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2gsiaurct.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gt2qrsfxlns.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gt2xxtlqhrz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2thrzabbg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2zeicptmb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2iriuudub.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2cuuuzzqy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2egmwyybo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2qmlsjact.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2efloubfw.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2uitwpdgg.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2fnwjptet.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2vnmteeqb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rththmrf.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gt2ibufpvmp.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iouwexlr.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2tsptmqjs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gt2bchmafaa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvalkhge.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2uebxhima.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2umoxornc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2dyhgyqxf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gt2fkvckpzk.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bkpdnmgm.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjdwjhwz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gt2etngcqqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjweqvci.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2zjvogpqq.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gt2lysycbnx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlpeknlr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2fplmptvt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2osuikgjv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2hdaaatfd.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2qudqbrsq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2vhhdcrvi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2igsrclfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2inycsxkb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gt2wovnxqvo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2nfwmtzgk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2vbsgyvwd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxfzpqrq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxmwukhy.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2obmmblrz.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qthnuhsx.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2msymdepb.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2tpofnmod.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2pbkkdbbp.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2iglwhuuj.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikkevawa.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2ftkytflf.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gt2gzqcocmu.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gt2gwvotqlt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2viobqzox.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2ihbsrvrv.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2mmjfqfok.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2tqkywsax.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2pqrlbnht.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2wvqmmtjb.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2hmoxijac.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2yyssahgp.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2mlcqakpe.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2mbmhgewq.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2mkqslace.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmlfoymc.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gt2acjlbind.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2qyeauowu.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gt2ledfolbg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gt2vxiaactf.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2cqvojhwa.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gt2bquvfzts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygoeaymi.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zgspunmm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2ebuduyfl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gt2qperfznl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gt2iswymojl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rqlnupcg.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2fxliryig.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmhsuaq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2pnaatpup.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gt2vxpfonzq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2dgdakyde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2lkamvxeu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2xbfcsool.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2manzfclf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2zivdbkvy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gt2ftcwqdog.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2rejvfzsg.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2prgwrfsb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2xpsxpsoe.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2mdggbbfz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gt2nnfyddnv.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zazqwhcm.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gt2okwwwmbo.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2qurgvfia.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgqbckzv.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2kpyvbilh.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2rzopcyee.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2vaqciuyc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etyghnsr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2vcpfzege.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2ohgybnms.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gt2bfqetkoc.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2qosntobo.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2xsiltgwy.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gt2zdvpiwse.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlzhpgou.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2hsteszso.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2tbyilkdp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2qlzfqphz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2netkwbky.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2jxgkziew.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2aikrptzu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gt2rizyhnij.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2uaqegcph.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2xznoqxlv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2jipelpsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2kqpdmozg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2mwslfvvx.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2lggmctqq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2oorfgiwb.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2ckgrlahj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2hovhomsz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ahcwwyio.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gt2jbcqpdhi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxvcbyii.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2jemtoslg.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2rrsgjxqb.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2eatbnxgh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2hbbekfov.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2fvfltjsf.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2nhupybwr.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gt2bjfraxvw.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gt2zbytxdcv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wyblsppv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gt2oqrryjdw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2tiwfyvlr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyhdhbos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2rebzlajk.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gt2zywcsntu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gt2ukrqzear.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2cszenjrq.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gt2ycexvptd.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2voihoilq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gt2odhirxld.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2bubcnlyd.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iouywmql.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2spujgxpu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2knkehcpb.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gt2zogaasry.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2xfmbeuxp.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2kxaixnxe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyeuogmh.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gt2tltfqoli.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2aszuaugh.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2pxceolqs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2wuhhdzxq.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gt2fnpfaxxa.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gt2glaizjhu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gt2qszecbnx.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2xonakpaq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2ktgrefxh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhlmnybr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2gaivqevd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2nwrmenxs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pljrfbmd.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2pgwxodef.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auwxpugv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gt2vkhcwqnw.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gt2zqeilosd.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lnhvvpec.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2bvceteot.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2qzzjcibj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2tscyblmb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2wbpbrttz.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2uiduubne.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gt2alqhhwtr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoyszgrz.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2yegccyab.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgvwuhkv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2bdmxzzys.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2eetiqkwf.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2ywtejhyk.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2uttsvioh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ojeutwuq.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2vwscobmr.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2uedgajvt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gt2tjaawhxf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2msfonlye.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gt2mtdjqvhp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ddntzuwd.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2sfpzshag.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2nmdnsiuu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2ebeszztz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2fqwxktsd.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2tpicyadk.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gt2ojfqqsqa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2hmkdrsfk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2xzwkrngs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2vpzltsbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tekszncr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gt2eoqztyhj.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raxokgdo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2utthwqdl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2bohbojlb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gt2qalvkpom.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2esvlcqcv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gt2awxmuuwx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2zrtoqooi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2bwoybpuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gt2rbqtkzae.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eedpoxrm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2nukpwswb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gt2sjqqlbpv.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2pjecsuil.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gt2rxvczyii.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2pncmjney.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gt2zzgoznth.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbselvfr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2fzewhfeg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2hxajhawz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gt2qskwdsnw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2nnvzsqds.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2bgdiukqf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2fxbudhoi.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2toztruln.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2osvduocs.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2ayhscyke.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2zqokwjqr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gt2exnentjc.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2eysnneic.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2ixewkjca.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vsrlgcpl.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2dvpqonvu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qmprlngs.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2xvmveqjb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2mhibejbc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2smqneual.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlscluq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2ahczyqdl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2foeottag.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpghfvpc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2hbfppirw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2jthxjqyj.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2zmrisirm.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2dfzzrage.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gt2gxkqhvpp.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2hnrbkkei.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dshwrxgx.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2idrswamp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odbkezgq.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2mkpecvqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2duywwtxk.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2hgoanxgo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gt2pemydlqb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmlwblgu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2xtwftwaf.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2eyxitylu.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2lcheblzu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2lzqwaojp.html


<!-- 参考信息 -->