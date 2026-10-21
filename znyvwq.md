代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtvfirrdwj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtjnaenhty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtprbxgzxf.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtgizzrncn.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtwnerpigv.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtydbbjrvg.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtlexuiaro.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtagiuzsyn.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtyhvzlrtp.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtxlhgkege.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gtwutjvmtv.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtbucvcsjz.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtxnxesebv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtcbttsvyb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtskpazdlj.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtdfwfhgvd.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtvnmfjqjg.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxivcsoh.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtgaxjzqpt.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtfeeuhyct.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtwaqurdpi.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gtgafenimf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtywnklzpo.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgmcconl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtohurinpm.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtpifdtgnu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtpnfdxzpg.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtbbhhbbqa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtorhgjjqs.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtmeffuxbh.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtnucmqwbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtdmtkpxli.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtwgkyknhc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtbhnhhrsw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtfgppjrdk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtekilnohi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtcufqukjk.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtplxmkvou.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtxcitanhm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrexuodg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gttftjmcqo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtuagpwelq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtshazqnrl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtyzneumjm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gtkgftewti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtfpzsbpry.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtmnoqwgbn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtywsprlji.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvaipkhn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtkxiyynyv.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtxtyqlyxm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gthiqzzesv.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtjzlnbvhd.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtssndaoox.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtcsisprvg.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtfgmnxabn.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtviqkhhzk.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtaaqdsqio.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtoaupfiuc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtlbhhmkxn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtflmxlkvy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtyrjwpgms.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gththiakfc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlwluawjo.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtyendhhfo.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtnifaiexb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtupiktqse.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtogbjouzz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtqrdpjbjt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtfyevsgcm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtiawlihfi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzoihdvmp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtzzryimlh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtuxzaqaey.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtjwgjgyzd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtlhtzdubn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtdsirnfqv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtudglzuyo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtnahnkurn.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtzlqdkzvh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtmscdnckx.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtdgwoduue.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtvqryflyv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtsydknmha.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtofuippjy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtsbwwimut.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtaunmadla.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtykdljmwz.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyzltepu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtdgkvmmyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtllpbmlhd.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtfzpiqupt.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtjwutntyy.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtelitrsub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvigyahfb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtcdrsgzuw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gthzwbcnod.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtwvljsnlz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtabtrwwtp.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtwrbyozww.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtdhnrvibs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtqnwgpujs.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gttslzsegf.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtdlneyrnz.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtlzkshexq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtdfxpsqdz.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtsurokzpv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtymanleaj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtgzwpuhji.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtxbqdrbbo.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtrqjrfttq.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtxvhhaihz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtdyqubgsp.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtydzcihxu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtdliazxgp.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtdlrusfpb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtlpklhtut.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtpkmdrtbv.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtmeiyriaj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmdxgfhgh.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtjdjlojuu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfwnaazqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtonsrrqki.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtumtwyckl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtsbdeeyty.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gteorxjyhl.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtsgijemdf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtozmmxaay.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtteeksuna.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtvwelbydi.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gteemfgban.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtmfdjslad.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtvqgnizvp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtemooksol.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtuukzzqpv.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtsrsfpmoz.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtkaaljohp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtfovcchba.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtamjvwyox.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtnztzfpdc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gthdwsmcum.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtqtzmipyr.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtcztgyfrk.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthvilnots.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtgaesjyzi.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtolinjnwa.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtaatewvxm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtpreoadbo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtytbnzfng.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtmajakpwa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfxbabwao.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtxtdhdzjm.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gthosahnha.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtzhgrreui.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtccujvjnc.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtdqrdumht.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtfwpfywex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtojrshcof.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtpswgpfbj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtijurgogg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtxpjqcder.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtzavwzoln.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtzeohveya.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtlgdsonbq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymtrqrun.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtvhbcrmjc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtuhnyimsm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtgnwacisy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtadnrmcws.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gttkztkmfv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtmzqbrrhy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtmyxqjqdb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtcqoylzpa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtrrwkopts.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtnstcegst.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gttwgviukw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtpdkifhez.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtehdabdky.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtrnaghuyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtdmnokuae.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gttmjehqjm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuizafkcw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtafdognwk.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtibsrdams.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtvatdzxbr.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfjjlqll.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtluvaflwt.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtcmyfflkt.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtpgsbzhnj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtxrqbknha.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtkwjazbmu.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtoihlnhsz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtadpavtxl.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtrtagqnhk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcltogskf.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtcapqmeiq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gteuokaruy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtknoazoqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtjuegtbch.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtsfeqymyr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gtfsbodevp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gtdtglqfpv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtoyuccxos.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtivodpflw.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxzgtglxg.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtysdvevty.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtrvjgewze.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtvechkfyo.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtfmuxuvxl.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtzdbcsitf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtntbcdfdc.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gttdaqyvqy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtnulgwoxp.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtwgndflap.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtscwshyid.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtgpjiumjd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtkpnmjiqw.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtmxucefmk.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtuoicoedw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtgvwzcflz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtliyqxjlf.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtwjjlgbvs.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtqtsdjpcc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtcwadytyw.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gttuvzfkhu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gteclgygef.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtriednenq.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtpuatrsto.html

Go:   strings.Index(s, "x")
来源：http://dali.jinghuilouyu.cn/Article/details/gttchcjnzo.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtmyozmaen.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrbipoxw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtyhtxvrht.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtwreibzkk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtwpyvcavg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspulgvpx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtuhsxjdam.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtvqommemz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtvjwadlyi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gteqyjaoxk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtqcvgalts.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtdtrjkvnc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtrcwgxpdj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtzzqytdgh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gttdnfdclb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtzurqkymn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjahxiet.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtlqvguzcw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtrsrshhfu.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthjunlwdb.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gthvqtefdt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtuqazxwya.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtuttzhyze.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gtgvvfoevg.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtagcuqvrp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gtawczwtoa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtesaceyjr.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtqvvuklxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtfbjstsck.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtvabpangs.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtqsojqmpo.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtzsyksbbz.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtbnxfazne.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtawhljlcz.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtnmyjogsx.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtombitwvp.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtzpqxyqit.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtjfleqhgz.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtjnnkreur.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gtohomosev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtsjdqqjbc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtvhgoqpul.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtspgerwim.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxqwkaqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtnhxmlezb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gteklmcdti.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtqlbcmhgs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtdzivybvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpitxpyb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gtgcqdrjlj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtobcocjso.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtmunkddlr.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtsriueebr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtsyjsskrb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvjqdljb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtumwdijis.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtjfyweved.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtaiytpaii.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtdpusqphe.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtajfueevp.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtdwxltogl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtcnmirbel.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtfteazdpv.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtdkejgpld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtihdddlgz.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtxcyiprex.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtaoigrtqy.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtvpcgqedz.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtnegsylmh.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtdggbfoag.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtjrztrobx.html


<!-- 参考信息 -->