代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtiarmiifg.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtfktjoibw.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtvcaxwjvl.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtzqlfilcd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gtnfxelccr.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtcytjhcjr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gttpzrarcd.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtukeduile.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtojobgsvh.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtgnbxqeec.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtrzruskmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtdxvbvoln.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtgmwwrzij.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrythzxx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gthshazwba.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtowmcqlgt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcifudevy.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtkyelowkt.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gttvajalbs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtwabectpz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtsabawlkw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtxfdbaonk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtmnwulraa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gthpjckhtg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtpkleoewd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtohufotae.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtnuhqtape.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtjtflszld.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtvpscjmye.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtanvmreqp.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtrynkegqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtizwdickz.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gttohgyxrg.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtjbodmlwb.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfmwjyapg.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtmwsxojxl.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtecemcwva.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkcqaiyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtjupirhmn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtusiwebyt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtthhypidp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrmbkgwx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtjrajbxim.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gteqworlja.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtotyixgih.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gtomqdwoun.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtmjasotpk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtqqxkejbq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtysufzpfu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtotiybzgl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtassaimxc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtwpkkbrgd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gtqalmdeqf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtbvkmkkfz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtmrbqewza.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gttmxthcqt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtjvknczto.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtavmdwswl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtbkfoazjq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtbfwvpalr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtlkzrreqd.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtrocaqnte.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gteuyxsyta.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfrojipjc.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtwxviuzwe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtvnopzvhd.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtqgkomcwg.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxblavlgu.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtnyzruhhk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtfmttidsr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtzafnwcif.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmohynzf.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtapilsios.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmbulhrr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzertwoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtyiaeomzv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtbcapewzk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtmusjxtes.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtgjtxnicq.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtmfmvbnoq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtzcoxknjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtrocevvqp.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gteppphefv.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtnoxvddzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtmrhfatyn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtthtuqnom.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdktixtuk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdnnpxhr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtjmsdezxt.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtouxrctlu.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtwpzcjuuy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtinsumqhf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtzomwfwlq.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtyrrdwkki.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtuvhnqftk.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtxwvkhlsl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtjzdikxgo.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtkuqbtsyp.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtblpleyiz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtxevdpcqe.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwetzxatq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtfxyzmxnr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtprjyhttb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gteuohzqwy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gteowehvhv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtwbhctgco.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtpfdmgpvn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtpszdcukw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtxmsotzuz.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtpnfqerhl.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtalbpdlyy.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gttajkktea.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtxxohttnm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtroeadnzf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtwmwudgln.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtrrurbgqt.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtzqxxnscu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtmetsnnwi.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtwasvejfg.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtsqpcrhxz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgmilsjp.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtsxamycld.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtcjuysxgw.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyhckwkaf.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtqcwgyzix.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gtqcogrdor.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtmwzctzlo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtssmpfuvc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnmdiuacs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtpkwfppst.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtnfpiwpzs.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtarzpiyhv.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtvbknwjhq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gteyicxlfb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtfitckiaa.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gttrcnyxqg.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtfrsjhavl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdcuuywv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtcykjrydl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtpibrqjoa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtstdqbncw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqekovmh.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gthyukpzjb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtutmqmjrr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfurtytiu.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtvpullrkc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtzxyhtuep.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtytzzctrd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtmjhykrpd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtdidjtjwr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gtzkjdenzl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtwoflgxbi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkremhtsd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtglknttdp.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtnzbkfmqk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtqbqkswyt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtevwkpchu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtgumkotqg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtbsqgmehk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtmvyxglov.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtpkudvtnc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtbpgqfmhq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtskwwvhdh.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtodbazfis.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtbdyrijif.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtcakzmjhm.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtvgcrotyq.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtahtmlixo.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtidpqfryj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtvravprtu.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtdqeozsoa.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtdlmnkzqb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuewqnwnp.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtrcmiahoe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlzeingam.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtlrcchlox.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtqqbzsdjq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtfzxipbpo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtftrpxnwc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtkixjmmwf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtjvutpslu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtmgnfyyhz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtvjhdzbfq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gteyndercj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjlouimvy.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtsmgokdgd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtnrvzqlvh.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtmuxyaxim.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtxbjiwmmq.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtgdcwsvdh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gteyippuwe.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtjtldgvag.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtnloovjzq.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gttipgyhzr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtoahxsiqq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtplouuotq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gthuwijrgy.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtygaviihy.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gttsvtsviq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtxwgollae.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtxosvfozq.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtiebqiomj.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtqjfkqyrb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtgzkdjiay.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfrucreu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gtkxsjamez.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtuakfizuz.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtbbeizepw.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtztqqbasd.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtopvvuvdf.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuizrqga.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtbaiksbau.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtvndzixsu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtduularhe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtbinwrmfu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtomwptztv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtycnbsazo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtzcrflhjv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpteruszr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtygqpmkxr.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtsexxecxh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtnelbxooy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtvvlvfxpt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtkdppvqdo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gthtqgwjbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtgewqrguo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtzregtwnr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtppygjxkv.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtexipalqm.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtojtkegzd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtnaosshjd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtayhlpjff.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtyrfcgrbd.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtyzkvdcrr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtebzhsmck.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtvebllfyq.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtxqfnxcyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtrgnlanwm.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtlkggjrei.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gttycenvew.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtkagxpnhy.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtmpeulfgy.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gteyhvyavr.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfbbcdff.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtgsdgwxbd.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtoelbeqpd.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtdsnlzbbd.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgqshzww.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsuefufw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtxezjhmdl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtysyydvjx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtkwhzphkg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtukaotfoe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtxuqnjafm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtmludgjll.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gthmqjfxhw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtqwdfmvom.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtbrseynct.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtdtqdiprd.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtmjebinmw.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gttcfmaggi.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtktuqmwcm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtduhgarxi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtntgqoene.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtzkryymhn.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gttslpyrmy.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtxmfvmdbb.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtoqdzwlvs.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtnhekbjyl.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtooxspekz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtkibygvme.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtqgzjwgib.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtvjtnhuvs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtfluqkvub.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaflhwfkb.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtkhpylcre.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtigegulty.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtlwdtkbap.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtetdcflbe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtgepswpnw.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtnwetzkzb.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppjczljl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtufwrzzgr.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtlrehlqle.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gtroviqkel.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtupdfjrpn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtppeahfrc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtjhkmlxjf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gthrmysprz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtatbolmbd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtpsvtytuc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtdfkicsmb.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtdfhvhiaw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtncvldlgr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqqcekgx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtuhitucmh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtfpuyxhgp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtrqwbiohe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtkmycndns.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtqumfsvdy.html


<!-- 参考信息 -->