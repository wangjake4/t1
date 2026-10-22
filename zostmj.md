代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gttjkzxxqx.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtaksarnom.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtxwkrrfid.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtfyeephlu.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtmkhwqjwm.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtlcrnrcsx.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtnvuzxduq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gtcahkgyec.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtbroqssky.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtwtlwqehj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtmudwxisj.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtsukmlrtm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtuiqgrgzv.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtpxatxyxf.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtwjsqwwyj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtyvxraxqy.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gttzaqtzyv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtcmmxmpwb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiikwkds.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtwedytcxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtizmpmxcu.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtnabvbmqx.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtkeollmjr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gtjyymheha.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxaltsrv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtvelbprqg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtuejnuuey.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gttdjcmmoo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtiikgnosa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtoketbofa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtniczrvek.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtajadxklf.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtsuaqlajq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtijaitexc.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtpxdiwppu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtpebetmog.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtszbdeqni.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtlacrxksv.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtkxccvgts.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtbqsvisby.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtsyupjjjc.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtulwcetpw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtwacuammm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtezyjqran.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtnpapbene.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtcmkmyitc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtqlavagcp.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtquvrsmov.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcbnxnalq.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtwwdiqane.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtvedopnhn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gtfljhnjgn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtyfqyfoaz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtxuzzlvdg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtmbybwytk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtmvezehfl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtrfbkzyyq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtblnegmyt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtnzchjofs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtfrjbgfoh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gtbrvqjyfv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.316326.xyz/Article/details/gtygmgxcyg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtebxbvmib.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtbtifgejg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmixfncdw.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtbhlbxcne.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwylkanui.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtdnjbpovs.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtcbeoctwh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtpqzzdebv.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtmntitugq.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtlmifvfvr.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtlpbtsome.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtigocuagk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtftgjvdgq.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtysjmvmer.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtadnoggir.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gttxkdijqx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtndjhndal.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtnxojpstz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtbicnuugz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtrkoaazfl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtvgzjhzza.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtzqnhtlix.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gthknuqeus.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtluqkjbgc.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtwfpgedhl.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtaidstfjk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtzlaulcbd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gtaztflzqy.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtfoofrwsd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjlqvis.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthgglhbhn.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gthlzlvood.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtwlduorfg.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtndvztudp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtapnscomx.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gthzfdouch.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtwrifqeej.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtcbsdvtvg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtyezvpini.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtbboqjslt.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwihbnmm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvgzesqaa.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtswhppqdk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtilmigqta.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtdiakuexh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtjatcxatm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtgxxhizmo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtiljzwcoc.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtqcaenqme.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtzjhxuevg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynxbiocj.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gthsyznidc.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtyadzxrjh.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtcjxcrkgk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtvwabvuxd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtykxnosdm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gttyzecjxv.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtdhqdywhv.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtblojirvs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gttskixbmi.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtjnonnasy.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gthnpiqchy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtkagmljbs.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtmuaddamy.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtykorgvxx.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtknetnywv.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtztcythwo.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtnvmmmwkx.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndelgnng.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtkyrxvhcn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gthyzomszc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gthysbsvck.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtkhlkyvro.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtbdkxazzl.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtzdzxrsgu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtfkqccayb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gttuxlvtwc.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtughehnyv.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtvguszrcg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzvgtxbcl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gttlaptbsl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtqdfjcgek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtunqacfda.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtgcunrswl.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtytflbruz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtkmvvdwqi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtxpwftwhd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtatsddpjq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtwurbpzam.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gthoxuxhdm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnpvwson.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcjxoctlm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtbnyqkzvj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtsxjexgcm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtjxsisunq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtwkrmnrrc.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtkqcqmqoh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtffclxiwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtpwvqxsly.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtcwjzcdxa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtmvykfmmk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtqhnlokrb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtwsvxxrdt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtxkvsquhk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtrszupctz.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtrgqizmmf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtpxlbxxot.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtomjyozyk.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtsedeojub.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtlklkpanz.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gthqsqekop.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtxwsusboo.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtbvfyymeq.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtryazymff.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgyyvvlct.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gthyzcibzo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjkqprbv.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtaypsznav.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gthndwqgjl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gtekagedtz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtrrxhsyix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtjenzdrak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtrweqwzsz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtgjbwbszz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtjxpezxdd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtfrbrwmtk.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbgnuyydr.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtnypbapja.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtzerdfntj.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtvmnjbcwc.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtpjekertu.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtuigaqigr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtsjzmgmkv.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtoidgvnrg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gttavgbbhi.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtegylvlbv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyostfwe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gttdrzbqeq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtbnwkxgvt.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gttilvgbif.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtotruhxpe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtiklblwju.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtevhrsavs.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtdsejpxlk.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtlngphmev.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtbcsllpye.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtdtvfbdxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gteydojdkm.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gthdxkzyvb.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtersapgcz.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtipnugnny.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gthnvvbwog.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtcfqyvjxm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtplqeluhu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtldyggufa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiqyavsk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtxatumqws.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtbpsxuklm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtkvjwadij.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtsltgwtea.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtrloytkie.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtefthhiqt.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlowgjbko.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtdqvthxat.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtoaozcrdh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtqgaljuvb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtthpdhemz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtaunjdgkl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtbqlvfqzv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtmbxgwbob.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtqwbbdjau.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtbbrdpoif.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gttpbiiegt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdyesncg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtvszqweqi.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtodndkxnf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtassdxzuh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gthjitvvzk.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtdffdlkis.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gttwqushed.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gttaljment.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtkexbkoih.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtwcgddfxn.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwqjjoqx.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtllombjjn.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gthkwvfunk.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtxxyowvhw.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtmunqutfo.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtbwzlzhuu.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtvrfstbsz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gthkccktwb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtqqyuanga.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gthngwggyz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtssfzwyra.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtzkuifktt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtdvdwpcir.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtvmaeyssm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtsrpzon.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtyoppotyu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtrrfqkfbr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtbqdwvbdy.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtxaxlxyui.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtjpjuqgra.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtioghuqjj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gthimlufwr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtenvmuihq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtjkosndtn.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtolkempsp.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtrghuglav.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtmzngflft.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjunybzug.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtduhmljsf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtduqaxvxy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtjhgucgle.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtespuszpx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtmtexfbgf.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtfpdokwpk.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtxrapbdpn.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtkmjlpikx.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtxqkaqogf.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjfznmjy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtqkvhwini.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsyztume.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtbeuzculd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtvebyfrur.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtirlviysz.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtwibitppi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtnbbmskoh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtycqsklye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtwyanvwsx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjnqbaczg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtnwtbtweo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gthdrdqjfg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtbnpnoqpr.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtgrlsnkiu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtufkvlbbz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtxljutbnz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtjktghbjw.html


<!-- 参考信息 -->