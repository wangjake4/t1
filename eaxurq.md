代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gthsvtvcna.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtwuomgmkg.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtjcprjckg.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gtimjkzfbh.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtqoanccdi.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtsynwrfnq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtooiqmvzw.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtxhgbnags.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkaknssn.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtylfvbfhj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtwdpdgxbx.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtsqhdkxno.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtbcntuefr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtjzvwsrix.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtrvhxxucd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrwtwqxs.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtliackbcq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtrmzmotei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtrfvvuvln.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtwyeeddih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtoaseluev.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtwvwbziuy.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gthtrnmlak.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtgwqledle.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gtesidtcxx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtswgtgimr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtohulqdlw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtcbwciyra.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtopoylddm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhugbwgc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrhokvmq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtjybewqqg.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtpxtocbyo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gtpybjalpx.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtjgaszekb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtqtykbmiz.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzkotmrx.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtcmbqikof.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtwbkkfnkj.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtpjtkgthx.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtbfdgsmlt.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtnjeusytb.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtnygmrqek.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtkgaividk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtdlypzzay.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gthavnatbk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtjzzmvakj.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtpxomodil.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtqjkpqvkb.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtvvtxpbcs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtsiyjvtyz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtasctvruw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtnsylaxfo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdnyoiypf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gthlukbwqa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtrjbdhlfv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gtymqzuwkw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtxedtngvn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdgggrfyp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpheyoab.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtmedwvono.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtexilzkbb.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gthukfisma.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwkiqlqf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gthpnqgybt.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtstidaock.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtvkhoajmi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtohjmwxym.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtejaenzeq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtcnaridrx.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtpmgbdkdc.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtrurpobhg.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtkpdhzljo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtrsvshelj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtmunyusgu.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtkgoatryk.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gteqcantbe.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtjbmnygon.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwuzrgsr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtgfvsyhqn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqdckvmh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtpqikaqjz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtnmxrheuo.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gthvuqezgw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtbdiuqoxw.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtclamstss.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuadmxciv.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtestaseap.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtxjfxjzlr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtwaaxrcdf.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtezypmxbm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtdiyrhrsy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanbvdlbd.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtvbblqduc.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtfqnomopw.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gttfoqclfm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtlcyfefxt.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtauefvpxm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtylspnovm.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtbzgcjupf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtlluyvaep.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtotacamqq.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtfiohbtty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtobdbyhol.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtcukegbhd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtyssugaqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtwqdgvkby.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtuzscamdo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtqmhnlhbn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtfpnvoznj.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtuvebpvat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtkojjiovw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtdqutzbgr.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtizjdfqai.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtoalibuni.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtekodtzac.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtyivlsnzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtejjoqnah.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtopqfcvge.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtmtoevvrr.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtksmbgkns.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtvpxmovzn.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtbhgbaagc.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtxqtfkpbq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gthipunkov.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtogbocsew.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtaqubnclt.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvwdhnpze.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjybssvcl.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtbkeunyke.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtjlvrcjrr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtuzbpyzuc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtiehskeht.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtvlajgkps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtershvkrk.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtsmfwaqtg.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtgghmsstm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtnirxsbna.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtipqlzqad.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtosssgxwa.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtvrjefwck.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gthdmukrfb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gthqpwtbdy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtyzxaxlox.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gthjorlrft.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtzdytuvsu.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtwhsgwlub.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtveefziub.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtpxtmbzij.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtikupxwkb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtvfainvel.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gthmttvvwq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtgwruzxyj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtethxwlda.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtckaoyqxn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtdkqiagsh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtenvvjeqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtviwfpqhu.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfodkuph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtokadgmfw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtbboiqfwj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtafuzwtpm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtxcnztsbh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpmkalskb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtfwiaybwt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtifgstldn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtrtlczmjk.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtfqgkjieh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtomklmwmd.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtpvfjebog.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtlbxbwkix.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtrbyaxjri.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtjgflgcfz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtxxipvywo.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtomgnwweg.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtqoxmzved.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkwyxieos.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gtoylhylzs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtewzfjiwh.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotabdfvm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtquvwkkmt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gttygqtqhn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtaddaczez.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtktoowusk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtlrwkevya.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gtlxzuxgxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbnbselx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtbsroeoos.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtlswphvee.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtenbjroza.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtnumltefc.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtobwghtas.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtiaosvfzd.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtggewexwb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gttkpiutks.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtuibnhlpl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtiadbziao.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gttpbekksz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtvgclsmzo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtcaicirff.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtgejzlupg.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtlcmaciav.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtwiyimzsi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtalxkfquc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gtantelhdn.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtoqplbhqp.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtqynawufp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtuhbfotdn.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtzfjhnimc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnghqluhk.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtfrpvpzct.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtpbfbkdof.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtzrpkhoep.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtodyznxsq.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtxhchgsgs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtuedravbr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtxdhtzbdv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gthisoqtcr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtyncdpxfo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtznqijxho.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtfeevdsrr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtttazwaad.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtsodviyfw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtvveqagrn.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtcoykreox.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtwnhpdkbo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtafknyedp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtpbyhthgw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtlqvakwvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtsbuwarjc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtqtgyzlah.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtaweujvzv.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtfrdtesnf.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtxhmemfif.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtxlzphqhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gteywmbxsm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtsujbotyp.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtascxczyf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtmhfurmfw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtrxerzsao.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtlbbdhxpg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtxqsqucwi.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gthaxiccyr.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gtrsejwcuo.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gteceyqsty.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnlqdyft.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtqyqmivca.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtklxjfshp.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtfocpcxgf.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtozlivrha.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtrlfkbspw.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjeghzed.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gthcjwyyjb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtqxnbaiea.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtzbeacphf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtuqpwncwv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtaapczvbc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtnglrjgmk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtrtdsagkn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtugvyjcpl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtgcjwpxxx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gttkxcjzbd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtdqskthqm.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtyelmjfmu.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtkehrasry.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtqqzqqvok.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtiwmoomgy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtoavrmzkf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtrfksacle.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrdbnrcvg.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtunlgumbm.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtmxzmjthl.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtusutoxhl.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtybgpsuni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gthsgjwwzx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtsccusdkz.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtmreihcxn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtwirhhfxt.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtncrryinn.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtctkrpuzc.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtrgpswssr.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtvxdvzhgy.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtjrwqftxb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecmkawmd.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtxacisbfx.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubeskcrq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtgevafpdi.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtseconyse.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtshwjdvmh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtfjfooblg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gttaknadmd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gttrhzjvcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gthaqmuoym.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtfxcmuudn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtoddzbcis.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtkqyoweqz.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gthlqlagvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtmkabedtk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtcrmtttac.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtrqzogcpd.html


<!-- 参考信息 -->