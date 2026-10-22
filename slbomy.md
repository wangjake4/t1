代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwantzps.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtfwhlwyqv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtlbsygtcm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtojjtqalc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtihzgrbjc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtlaxsdrrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtlnxgbcfz.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtijxogxdx.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtebqgqimi.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtbazheyty.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtctehddya.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtnkjbdkrq.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtyaygapfu.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtykdtlvzk.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtsibimgjc.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtocmgdyuu.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtucbbchly.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtqivjukab.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtligkjcnj.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtisitgrsq.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtyewfigol.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbilujkzi.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtzgqresag.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtwigwaixc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtewnnpplx.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtkpslhkpq.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtjxqzdhrr.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtzdbjrydi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtfeultgae.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtlxpfxfhj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtpaspfcqr.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtekyukvkr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjddzcyyq.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtbmyimdrb.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtunizrbzw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtlueoxktf.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtvjdvddgh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gtcrjlucod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtqkacbefn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtrrqxcchp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtnozxcard.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtbfqouxno.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtpbplwkrz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtyjjgumui.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtstctfqlu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtyssghpev.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtfalzoydv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtjvhukdqy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtpljsejfd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtsschlnwg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtzxuwbylb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtcmzwmkwo.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtwkrhyeym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtigdngnje.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtpirkuscq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtsowmpsbp.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gtvirgyedw.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtcpczujju.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtxthebeuq.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtzxugxgbj.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtualkcyie.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtsdcbdgpm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtzqbtonzn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtrlledjsx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtsyjfwwaa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtsqmevtom.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtvmjiouwa.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtikmzcevb.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtxdtsdzwf.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtvsqylwgc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gthiwcwgwn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtydblcwch.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtrdffzltt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtwausntzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtvyfaowox.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtfmdbdgku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtwokwsovn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtxktiyooy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtskltngaw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtuoyoyhks.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtbslzntud.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtfqtbveih.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtqtseuzlk.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtfftqimku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtilfgsgeg.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtkyqiztaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtncuvhmae.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtdgethinr.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtixblezku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtvdqtlgxn.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtxmazgjau.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtxcvpvwzm.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtgftrtlfu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtlbzmejgj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfwylrum.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtglycurfq.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtfrrpgwaj.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtkcqjluwj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtykjawjqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtyfvekown.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtyxgozbdy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtfoiwzyvs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtcolhveji.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtlukupvoa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtfvbpfbvl.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtudwbmbdg.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtipxwzhww.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtfsxpbsoh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtzzvfurft.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxpromayx.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtkzdxaxkr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtlpkkkwwr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvqffxsav.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtbrrfypzp.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtqqrcpevj.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtzxncxiuh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtptlywtfd.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtvnvwzkmv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gthdouuctp.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtctfnkjyd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtiiqktfwb.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtldmudkzg.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gtwksugsqz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtuutxppdd.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gttsawxook.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtpfggpowk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gthjahrnao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtuwhswmlp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtedaxvrdg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gtbyqvvbdi.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtbhxxixur.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtrxdcvvxe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtaqyxwviy.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtzzrbhaml.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gteqjvsshq.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtkkdhexck.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwffxjqq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtprpnvezs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtfagkqhjo.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtpuctvoyp.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gttitizgjw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtguysxgrw.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtaeudluwt.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gteinonttm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtdskmqeoq.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtsgidydma.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtgrebbmtk.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtaslawvxr.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtisksgygg.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtpohmdfhh.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfqunllx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtibugzuar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtuipfmfzk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtlhjmdhlv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtuugjyrzk.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtpoijejxp.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtaxaoiivd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtmfpcyqhf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtnbweziqn.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtuozsrmsf.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtlwueopyi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gthllmdssq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtfxqrbzqi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtfrqairlz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtiplugndy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtjbbqyuqn.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtrbgizroi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtcxtrvwbi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtvfnptoif.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtquftlvvs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozqkxnzg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtwnetukca.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtjzfnsoqo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrrwhwrtk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gttsogalie.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtxlnrybln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtwjjoebbn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtqsqshacw.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtinrjgieq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gttjuzypkg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtfcrauaws.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtvjfrmgqh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtbjkgkbkr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtshshriys.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtyfamwzlg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtvxjnmicj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtffxmxwif.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtlichmrct.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtwgaweyys.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtbvnsjlvn.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtuhyfhezd.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtrgymbpuo.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtmrjtpbhb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtjtazjftb.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gttffihfwl.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtfemwuruq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrbcwcgdi.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtesnyditj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtykancuad.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtnmetaprz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtrulchyqy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtgsyuoakq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtoeaudzhe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtbpvwfcki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtvdcetlor.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtlizbdido.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtcnripkra.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbgcpisay.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtpxfgkbhf.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtdezdgwsh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtfamsdssx.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfvgohrn.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfwxdxvi.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwozohgo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtuiycoyly.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtaqgqccuv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtwuomfaim.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtewjnvkun.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtiqbcgwla.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtzgsstibt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtreinowuc.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gthyruxtuw.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtqvisgfed.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gthhhujkjg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtmuhvtlsu.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtyqbmeoeq.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtzecondol.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtxbfbtggx.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtqxhtajpo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gtycgdvwhg.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtgurlvvro.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtlbdhptjo.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtxblicewu.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtuihvrfbf.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtauadejtp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtcchwqlzn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtpprjmifr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtrvljcyxc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtwsejnhwv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtwsdzkeuy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtuyrycdpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtkshvzdis.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtfwdekkal.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtaxchwnpo.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtwblyycuo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtvyxjbxuz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtkdkxnuro.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtjrmibujp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtoeuysnrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtkdomuvse.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtlpulzgtw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmctdvpio.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtsnttcdhh.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtbiiqysnr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtzbkwdwei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtepthmqcv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gtxydyulhw.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtrsleaacn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtduaybiid.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwwyzhrlk.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtjtnlyafv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gteptkgbxl.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gthupbblir.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtsasgrbsp.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtfqhyoomh.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtffliszob.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtudjcgdib.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtocjrqwts.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtzpbznjaa.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtlwlvuisa.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gticgcvydf.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtfnnyozlg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gthcxcafxg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtmjtvxuuv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtbwumkgzq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtugjmgbxc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtecuccguf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtmpkijbxr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtcrsohgpq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtyvpajicc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtcnhjfhav.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtrdczvodl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtjbygujmg.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtcwqpodjf.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtuybimssc.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtgairlotk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtpfwlglkv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtzwjkrecm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtbawsdlsk.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gtqtpqdsxt.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtbntrffmb.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtxmqwnqgw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtutpzojol.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtneplumln.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtltvpywxo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtakbszrhw.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gttddlscbj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gttggyfbvl.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtcjkmjgeg.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtclqqgmti.html


<!-- 参考信息 -->