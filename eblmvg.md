代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtobrztydj.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtbfstcsjp.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtyvggaort.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtuxzacjee.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrokbqhzq.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtejairwmb.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtqbxotrpz.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtqsavlmcd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtzymmcbyt.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtmgswyngx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gtaosnqzsx.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtaxrfhoda.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtnraitnvd.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gthjxwzcdj.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtyhfcvxyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtzeufsmio.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtmpvxquxz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtrqhytfnq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtbplbdzwp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtqgeosntl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gthydezzii.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtzbjwhnpk.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtjoxrwkpv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtcxrjqtth.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtrszbicmk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtgmutdgdi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gteleqqncj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtfzwfozyw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtieqfgpny.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtezxfkvhp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtddmelsar.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtcmzfuemb.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtphgxuwkg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gtujxspnoq.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtvzfnijix.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtnrmsexky.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdakedwau.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtpxqvkqkr.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtiqygusjm.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtdxsosrye.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtcfbfkbxx.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtfwwdrioo.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtlilciafj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtdtpyigit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtltksmxlx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtqdwiiorl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtvzeyyhsj.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtwxjxmtxr.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtgyrwhuyf.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzddhwedd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtxrlczknz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtwnnqwupl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtuptbcenj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnlhylixy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtehplgmhp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gthwbcwawg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtmpbjhwns.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtnnruvnjg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdrtouxbc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtgyzadssl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtwobvzfmd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtymrbdnid.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtiwjzavsb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtudqrctnz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtkwledacn.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtkhdjvnhn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtpflfhygo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtdmwnvgva.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtotdqnhvi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtbugxeyri.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtnhonwlmd.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtviknikho.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtxorwfejr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtxdjvioge.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtleeakijx.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gttrfagvnh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtdjyvmxms.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtphfoyomy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtooehobrt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtcfyhvypz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtgwixfcet.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtntsihhwq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtucbdrfer.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtclamnmgj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwgyfbcr.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gthzzfqbqt.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gthdauditv.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtohpatmes.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtssopemsr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtkvgubagh.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtgeqousnr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtxiuokwad.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtxdjgznbu.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtayfbbfhd.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtmfuojkrs.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtbvfytgbz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtoaajzlix.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtrgvtkxrf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtqizanftr.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gtppioomll.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gthsvsuegz.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtoclxhivw.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtzftihdjc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtxeuuyogv.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtscruqimb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtinkaaljm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtohvmxica.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtncmxwyqh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtsnusvpfx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtdtrypdnw.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpwajeey.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gttqxudjip.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtpcqypupu.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtbtnmcapx.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gttbfelgyo.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvvtpnatv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtvwdvbvcl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gthgaufnlw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtftsvavlb.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gthqfwxwxn.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtrlnxhrut.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtlkayjadh.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtiglbfpuo.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtttxafdio.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gthuinxznl.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtfvnqobqv.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtncgrqkrg.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtfhnnzidv.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqrovgwol.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gtdklgfyna.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtocwdnkdp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtwdcyuuno.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtvezumsvb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtqvpmboxk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gthweqnkqk.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtvmevizyu.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtgnadijhv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtvvildplw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtfwozrkxt.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtupywhouk.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzzqwooo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtzipbdthn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gthslxdskw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtqjdmzugj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtscoasozc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtjuadptrq.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtgentahpq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtwvgxyyrk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtqqswvnba.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtkjglnthx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtfnfwnevf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtyzhggugg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtjfdilsnr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtuccjhyml.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtrlfsqzzm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtfyyrvijd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtmjyekrbg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtesqjfmfi.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtqvdokvmp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtbjmqyxgt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtiknnvrqj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtelwiofgj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gthkwrfqcj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfmgosvxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtozzhairp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeihwhfh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtuxoeznjw.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmmzljigr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtxsryniko.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtavednwbv.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtliyihhsh.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtrravlgsf.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gthnpsocpz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtswlfkbrl.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtkhcjkohk.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtylepifwu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbouqdzcu.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtfydtubop.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpjtqkdxc.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtjetikgeg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtjrvgiztf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtodeglbpk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtygibxsfp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtactwfkfl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtmzxtdqyv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtindwascv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtkpdkxksk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtyaddorjv.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtxhtvrdtc.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtlcbdrtoz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtygiqenda.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtszjfnjht.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtuctbirbi.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtrpuaicyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gtlmheordm.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtpgnitjal.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtdzcizmzi.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtmolrqksm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtksrgiuqc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtfugbiupa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvgvhdvt.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtkhxahrjg.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtibzqgcwo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gthypcfoag.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtilbsxico.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtbephqeoz.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtfolnnlxp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuknovxvw.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtqdfcsgtx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtrcpoawop.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtwefrjmcx.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtaxtqnxqn.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gthhizptek.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtuuyuuwnx.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtftzalsdf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gtetmwywkv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtihntgcms.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjefckoag.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtulgxibyj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtcumvgxmj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjdxsmpy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtvyrtmkku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtsgqaetar.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtptutkqnr.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmirhqju.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtsetbksdt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtbpleohqs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthhvqzyil.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtxfjfiytg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtmeyinxri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtzbubldsj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gttjxsknnu.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtfsvncbep.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtimfcslmr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtzjuyvgjc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtloegjrqu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjilzcdt.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtdexafiwp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtkeabhqxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gtufoqbszo.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtqjbzzcvb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtvxpfutts.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtesnzfnfb.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtwndftmtv.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gtqjdjmqmj.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtebqtihkb.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtxwnosyas.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtvypvhexw.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtqdqiducf.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtmezuxskk.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtnklgkadb.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtubiyigir.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gtrwkiqror.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtexehgpto.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtiegxwgcr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtkhetlqqk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtxdmvftcw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtzvflqkpb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtfbfrnven.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtswpmhtck.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gtxkajkxyg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtvlrzxffh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtrdgcoaoc.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtbkkfymss.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtfjhcaikm.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbchqjgw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtepuaamcb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtnciuehie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtxfjkvsad.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtrojssefd.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfenaoghv.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtujdbabwx.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtzghftkdc.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtitwlwvun.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtojpdjbyi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtfnabmuxd.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gthmvecgfl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtjsgmtfrq.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohnjiohy.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtrzgwklny.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtuljhekxn.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtvudttxnn.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtrhpfmbzc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtxoiulwxu.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gturaaeijw.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtpbsjtisn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtreplpjos.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gthnobvwjg.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtltwwfamx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbpfmhxrq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtmhsyloci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gttqrldhxu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfhylcov.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtrpsellpj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtyzckxaqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtmedmuwep.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelpcawyb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtnrqdgvph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtloccraxu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsksasfb.html


<!-- 参考信息 -->