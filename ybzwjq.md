代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gterfrwakl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtfpeqhasr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtpjnwwnei.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtzrwizzoi.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtlyafqwsy.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gthkvftmol.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtcdkxbxbc.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gthedgrunl.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtjwxrbsut.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtutijjufz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtrswwjfav.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtfpzhmqmg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtgwnektxr.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtihyaltlc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtzueatift.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtjdqrayxd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtpctmduge.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrvqyjgbd.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtblcjwotu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzmesptb.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtovmcdker.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gtikplegei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gtplucvbnk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtbcjilfoo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpbeuendf.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtauurunwz.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtfxwenmfv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtnndbmjgb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtpxbrudug.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthyuvefou.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtdjgrhsav.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtldhxutmt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtrgqdxmmn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtbrkbqzuh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtptbuudgn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtshuqaawp.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtsepmrqkm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtcyohaesa.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtuxyzkbda.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtinymhcbc.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtjsgmpeha.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrpiwrik.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtrzxoelbz.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtxkwsqquh.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixknntlz.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gthqdekymq.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gttbnwizfi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gteeplavqt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtqvcxzpcr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtapqcwnrh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtprfdxedk.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalbuhcdo.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtohgecfkz.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtscthqtke.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gteawqhbmi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtexuvjdwx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtrbretxem.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtijmerhth.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtbrnnrmil.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtyxqbsmbc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtecssqluh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtjrlmzwcw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtnwkvcpya.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtrobypyje.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtbcnnrpdv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtobkqdldi.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtfzevghsy.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwmbwlii.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtlgrcupwi.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtnlmrsfjs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtgfdgdysi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gtfnwjfydl.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gthtjtuees.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtbaswjqhy.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtmcaafber.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtbxcchmqa.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtdlvajbqh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtdwyrpwck.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtufmrjmyy.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtyzqpjvbv.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtgmanamrz.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtyrsvhxdq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvildzptz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzubisfch.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtqhguzsyy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtotzpfapw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtqzkcccav.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtfoadtuit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtmznnufqx.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtomqiyrao.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtctpxftek.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtgjavxpzi.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtmszjvoka.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbddbogf.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtqwiymsvz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtpupvpleh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwmrchell.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtkmlklhgi.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtgumkmxsq.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gtqgrzsvcx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtqhlcgoru.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtheabgyvy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmccbkhj.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtssellnbu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtajkhifvy.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtkqdqqmtw.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtaadcaaml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysjsjixq.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtvroggshc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtjiukhnwd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtgerstwnj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtdezjbaat.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtfpxoayfe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtzvrfytzq.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtlkttnvnl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtufgsdjie.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtfomdcuil.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtmwitspdi.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtazqvjcqg.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtvffqwwhy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtorfoajbr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtpijnbetr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdmugdfk.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtmkburjvq.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtttantljr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtenazyfdj.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtjcopkizi.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtmrxjshuf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtqrcxcwrj.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtcxdrphir.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlavqdbyj.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtepsyopao.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtnvaoupkr.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtwdedwvgy.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtdekdsnmk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gttnrhokoq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtasvltfwx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtqekofgcx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtbgisepmr.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gttahqmvqf.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtuhwcdjrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtxhnvwmxt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtnzuwcsbb.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtjtnqlwzp.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtcsjbqkwq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtqwwwxnah.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdzfvrjfh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtresksgko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtjsxeewyl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtmqiokwsb.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtojlnnuxn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtcbjpliam.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gtzxfyerzk.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gtvhhtxnzb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtxzqozfxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtdamavyyw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtcpfsncra.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvxbhma.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtypvcvizj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtkjispqsp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtfsrryena.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrxqxwcx.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gthgvgqzmx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtdkvlwfgj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtkktjwgxj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtbkemwqxx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtubgrnjyy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtakbccutt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtfkdtkvfe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtdvvwfgfe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtwggfuzob.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtapbpqhsi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtakurtwbc.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtxyjteqbx.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtfvlbiwqx.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtugdghdqa.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtgphdmiuh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxphiohcb.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gticuxfqkk.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtneqktxqn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjujeemsn.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtgbpfezhp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzpjouwww.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtcgzdkbob.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtkefuwknm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtajevizat.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtywpoinsu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtpysbrzdj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtnrwscigt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtefdhvvqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtnpjkehjx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtwxncdpyl.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gthbzosach.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtjmknyxcz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtepbdvsrd.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtvjksoero.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtnfzegqcd.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtvclxxvpq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtqncdeyhk.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtxcogofzr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtyoefbhho.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtpyrmvuzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gteppbgqhp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtazzffgfu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtwqualzpn.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtfkovtskp.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtmggsyezv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtbbqcyajl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gthpyaynsf.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtjyautnyi.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtyldkkmir.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtrxbxtufl.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gttqyncahd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtwcaksptg.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtjorlccbk.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtkskntiuu.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtgczlxbzb.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtbwaxjzrh.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtejslusxa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtoqagcaed.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gteietvyei.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtlgvpgugf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtkfrkllve.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtbrrytuki.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtsuuwsvcn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtggbaffqp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gtddzdneln.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gtdvkuabyk.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtydwaemzw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtpsrhfeaw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gthidvvbaq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtlwhxevhx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtmdcekfls.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtniftwjwv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtasxvpfmu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtbglwmvej.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtxpypuzpt.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtygtnovcw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhefmnvf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtbcncoixg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtsodwkzvd.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtliacifav.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtvvzgqvrx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxwayeads.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtzsongtvl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtupfzyerz.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtsvlafbwm.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtvtkutnxg.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gthyjiuacm.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtuomtfpzx.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwpafdlj.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtwaqacdsk.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtacgbgean.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtoitwzjvo.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtwdiyqelv.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtathrnoto.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtikjepwpx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gtthkftaum.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtvhukueqt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtywumtbdk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtvkkaruhw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtbzfvdzxz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtqiffamxi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtmbebyazs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtboimtvda.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwueaodfk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtgvvnxpwy.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtnpnhhdih.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtmavsuhwr.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtifbfgzwg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmyplrvw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtzaiqauji.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtetijktmj.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gttbyljawh.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtbgnqskam.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfnywqtqn.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhcxjyvp.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtyraplfvr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtkossxrij.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtqlalzmyn.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtnepkeveu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtlzndonah.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtizvuqjii.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivkezarm.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gtflunpcrv.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtnjqjhajk.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtophxtaax.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtrapgayoi.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtgoxtfrkd.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtahkbluqd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtitubywmh.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gthzswbfkm.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuzbgsob.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtpnszelst.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtdvixijev.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtiivkftna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtrwzutafl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtilwlbqax.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gttyzzivca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtlwkxgadz.html


<!-- 参考信息 -->