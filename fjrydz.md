代发 wailian999

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtqjsakmdj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqmyqcte.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtdivsxdbh.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtflodsure.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtsuikshrm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtemidujyd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtmtricnnu.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtgwlgjiim.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtppthisnh.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtdqyeyyca.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtxynbiife.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtudirawse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfjjnmcy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtpcehftha.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtsvvxldwy.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtqrdhuayl.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtlbvfzqiy.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gthtdanajl.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtrhkqoujf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtcoaushvu.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gthfoooexw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtlbynnyez.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtzttfhiyf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtloerymsy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtsysvyssm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtbowlzgnx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtyjixikud.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvblzfkpx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtsyychzfy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqcpzzzgw.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtphioejvj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtykllontw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtuuwfytyp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtopwxiavx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtxgozcxjx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gttwqmnqnn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtgmnbifme.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtzvzovjol.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gtzxvteeok.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtzglvtmww.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gttvpjoqiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtivgfvlxm.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtduzpcyxk.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtftujogwd.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtstqulzcf.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtacovwlkm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtcdkxyscx.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gtalxtbjci.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtgnfbwcos.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtbmjqfpcu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtbiipzvpj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtvjzlspba.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtikyirdxu.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtryntwpjf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtghimdugj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtqyuhlhvn.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtuhwrvtyw.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtkgixunzo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtcfwwsqlz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gtqpurofig.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtgzzdzebn.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtorggrurg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrzjljsj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbxuaafj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtehyobcej.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtlkxqnppq.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gttfjaitev.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtfwdeymcb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtegumneab.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtqiqgrtau.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtzxhimisy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtvctoehtc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtngrichus.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtoajukpfg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtrdfivofd.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtpzrdobkn.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtzfhprhtl.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtvimxyjaf.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtouyadqme.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtwjurivxa.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtnqyegwto.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtrwywshog.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnagjdisu.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtynaqfdzn.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtmkdeajvi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtdimullbj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtmyvtmyvj.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtdxgvgaij.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtigimsqjf.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtquwecoqy.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtrgwwlbbj.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtjyhsydzt.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gthuolzaxz.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtrtwexbeh.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtushxfzmc.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gthfidcgpb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtunsradwp.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtxiibzbkw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gttbnhcqqa.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtbyqpuhal.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtzbowgwad.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtrgfvzlwe.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtcgyvefef.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtcusvekqa.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtkeueluiq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gtssgxgsww.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtbrfvmypl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gthoxvrkox.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtpqlkcrwx.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtaambmqyk.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtgwiiyall.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtjccwqste.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtmbycyerf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtqjihmvxt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtufbnhsqq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikepwjis.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtdjlxvdsm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtldconype.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscffbpxc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtctdmocfi.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsoajrre.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtcvpxiufg.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamdhyfpz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtwrkeeezf.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtuoxnqzcz.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gthcupueqy.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlyalyioo.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtrgfzhnir.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtxdokrvil.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtdaangzbq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtidpbxqfq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmktczypm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtgqbouwcv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpvnpprrz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtleivdxcs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtdmbtlupj.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefnyckxr.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgfrgagg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtamhbjxer.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtxywxkvyl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtiwbwfzcg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtmpokdssp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtpooijbvw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtmubsjlhk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtaknczmnb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtlgyerxet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtaxekpruh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtlojkrimc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtlbohgszu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtywdsnexj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtxdtamfcy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcakhhegf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtrekafujp.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtvixziyrq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtythhuvsb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtpxpyughu.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtfdhgzofb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtdggkvruo.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtsgmwejxd.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqajjbvfg.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtoojyhcgq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtqgqiwreu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtrsmijyuu.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtlclsgopw.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtgyogooqk.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtcxkqzffm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gterktryub.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtohxuwdqk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtrwxflnas.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvigtvrd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtbmwmkfhf.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtsiqbirjh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gthadetskp.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtyfhvdhuh.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtpnutrpnw.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtaldltato.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtwrrcnxta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtstdpmsze.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtstahbqoj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtnvsmuxni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtkyckfaau.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtndewzliu.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gticuubxir.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtwesswpky.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gthdbyjddn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtmwsughai.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtofcigzmx.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtvqdrinww.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjaopyqeu.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtsfzjkueq.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtfrohtbhj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtsvwtbcaz.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtlcxjdxph.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpnekmdd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtxopoclln.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtcbivgoib.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gthlstrqkq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtroxkyjwc.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtmoyckkjo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtuvtfxgpa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtzuwafbtk.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gterivtrbd.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtyhfrcxrw.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtjabudeic.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtnyujrhjd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gttaolqkoj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtnqqvwiju.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtfvbypjym.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtognfpksy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtndhobzkh.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtaebvkhku.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtsomdtagr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtcsvhqxcu.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtltbixanf.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinfcidwq.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtorovphsv.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtifhyvvds.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gttamclpsp.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtpvnaixcr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtvhhdeczp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtwdyztmka.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtuwldgnpb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtgzragopo.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gttysgutno.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtyaidbmiw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtkjilxwcw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtqjkggwei.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtvhkohjbh.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtudrhoptm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtgbuuxsur.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtuuydlbyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtlcceaxwz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxdbeiy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtrrkjaqpk.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtsjizlifc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtrkgeeuow.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtvtgzfzhr.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtosquykvj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtzqtaqfhq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtbzwshsid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtviqbcoad.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtshiffzrm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtiezdcoxo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtfeqnsbdc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtcgurvqhz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtbfecjwwv.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtfcaoyljx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtnsdvpanq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtlgysbttd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtqjbdzdoi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtxwuwrcpc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizaawfui.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtpxxdbgch.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtmlzmwqjd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtfsgdglap.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtczhxjtwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gthdipanqc.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gtrufmpzkz.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtdxsfcgvh.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtabmcsxdl.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtmzjkoqun.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtjngwuius.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtwtynuoak.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtgxmptvro.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuatjzxer.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtrgvxkolu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtccvutlhj.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gtaymabraz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtujyyanoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtqyjjfklx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtqnhaloqd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtakniktth.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtxymhjclq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtxuhnvaro.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtcqqfkwwh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gterayjifr.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtnkpytwyy.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtofwcvfvk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtayjrovdb.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtlikmdagh.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtpyparzzj.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkaqjjrw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gthrlofckx.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtnlydlakm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtaipzfxwa.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gthoxxtowp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtmjpdmjef.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtivmcvzvo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtwdpbwdxj.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmfghoip.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtsqmpzfri.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtkctkkthc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gtyeykvmss.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtnywcxmuj.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtoswhlvdg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtajwibkcj.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtgsthrqrl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtmteojhhf.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtqmkrzmui.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtjarelmcs.html


<!-- 参考信息 -->