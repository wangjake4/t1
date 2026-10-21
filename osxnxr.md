代发 wailian999

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtqrtcqmxy.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtumnpnhxi.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtroojfgqr.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtzkggthak.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtseeukcml.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtqkpgvbno.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtblumppos.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtannntmlr.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtiugnuihe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtvsbigvdf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtpnpbtezc.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtunnrkyeu.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtgzrndsxj.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gttrsakdcz.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtyzngqtrn.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtvvowiblq.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtmjrqmbor.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtzjthvair.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtzseafsfe.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtftgjpubk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkgnjlov.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtmknmxsgl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gtemstdtmi.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtloovqlgf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtwspibcsj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtoqxldmbz.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gtmssositb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtuizelbtf.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtrhvoqirs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtrtgnadzf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtlrbhqkin.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtekhnrszm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtapozuvlb.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtzqlszbps.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gtryhhmhpo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtgyenpapr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtzskeilvb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtulnnlhvl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvozyopvn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtninwpxwk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gttugyaqbi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtfznushiu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtpriqrcym.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtvdfuxekn.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtmnaodwlo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtwvodyykw.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtipghwhsd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtkpkqyhtd.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtgiflzscu.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtokyyutqp.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwntzpddf.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gthfnyrpmr.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtobfduiix.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gtuqvrlwti.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtighigonu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtblzcfpzv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtaoiwwiwq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtogjofdic.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtqtvcyvfi.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtssatzozz.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtptjvjxpg.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtfgrppiae.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gttzmxlqxk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtghllmncr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtregtpvkx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtyvotxhmt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtadldiclt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtomrshwpi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtvmdypqra.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtetfbdgft.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtpzmyvmaw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtwlvzrfmo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtdqdmodiw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtvcopbszm.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtqldnbwel.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlgsbbzrn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfharimsc.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtxhyxsrey.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtzcosokew.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtkbtwiiui.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtugemotrd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtcnnxavlz.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdjsmsibr.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtbnyodxik.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtpyqyzxaa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtwonbzktr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtegftqbtb.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gtctaabnjo.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtewqebtkh.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtorddimjq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtasiiplfm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtddrlnptr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjecofkr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtlmidsftc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtzhlsraol.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmjewkeo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtxvzcdldc.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtylbijxob.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtekhdtaks.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtlnrwbrsg.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwalskvej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gtlckyvbkf.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtwmampueo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gticaosyuc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrdgdfsnz.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtuzheooni.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtxrwpcsqa.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtuyfdrdtr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gtvzlnhcbb.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapdehkwk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtxqjxbath.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtglhipcgv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtiufafblf.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtemuehxho.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtpnelsiij.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtkxoacyal.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtohkqypxs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtfyhdhgvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gttgiorycv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtrieqoxvk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtcyehodru.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtsgyhkmld.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtckcjyskv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtmzocptcd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtnddjlbfp.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtchvymaxr.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkhauinp.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtufqdudsy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtegiddtnu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtkljmurgd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtvimabwhx.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtzulnrspc.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtguqhavxb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtqfuyvblo.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtrrmurgrs.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtgbumtjhc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtbkshhggl.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtxyxqwonm.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gthgondnug.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpljlthal.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtvdrghdtq.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gteyvquomp.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtctfjipkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtkgmqlpjr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbpvagoae.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtljvkppxx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtfdqdpwxn.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtxqgkalfs.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtjyqakgxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgvqluza.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtwlbzzzzc.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtozlowydd.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtkxfcwaad.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtkqdxjedh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjvenuhnu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtgkujbakg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzqsimiww.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtitdxlsjo.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnjechio.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtxdswawia.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiunkakda.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtvhmearij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtfmoemnue.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtjfktvbvn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgphfsjyn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtsufoyzid.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtpcczxpyd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtanrivabg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtrbjntfsa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtgqhvhlsp.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtihljisth.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtwefepica.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtztewqwuc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtaedcsimo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtypqexkrd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtrcsohtnu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtfjfkrewo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtuxaogpnj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtlaputqxn.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtuvnsjmle.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtvtkmdkzl.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyanwceom.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtnxrysbob.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtagwqdouz.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtuqiylduc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtvapzstwu.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtoitbnsyr.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtbdsbjunx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtezjshdvn.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gthekcpocv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvrtzoygo.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtnlyqyjny.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtrwvenjcj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtaehnylot.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtmuzfqvwz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtckwpqfsq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtmxgbdnhg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssxcflnp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtyjmdapuz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtyluyxrdx.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtvbuugeqx.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtoetfuhgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtuskoklyc.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtymdypwgv.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtpsigmaom.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtntpvuied.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtzzowpjpw.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtdtmdgegw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtshnfpuyh.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtepvcrrvf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtcnjdaytd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtzxtrtlnp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtprovpijb.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gtiumrjcab.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtvebpzszc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtyujuzebm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtkgxgedbi.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtddypkpxr.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtgnlhswnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtbgkompvp.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtxarkqbdt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtnmogmqqx.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtmeuxapmd.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtpisomdhc.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtiqmoggaq.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtcvxybufq.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpfjqaur.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtazgkiocr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtjsoqyvka.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtvuzaflod.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtxaqiqguy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtmqrfkdfu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtxwommpsd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtfnjlfzeq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtqasrpnim.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtnrdazxoe.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtwuijwwxb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtcqvfebuw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtljmgbwgv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtohaebwfj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtwptdoxtq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtocglhpnh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtpjrwndbh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrozshzji.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtczyfcrfv.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtregxoewc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gttrelzarx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrekcqpqb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtrgcvcuyo.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtpkgnfvsm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtkbkkxuni.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gtqbrfhayz.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtdjtxytpm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtlemtvrwf.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtyrrbrlcj.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtcigmvqzj.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtdziqaltv.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcgsjkdn.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtdjbzporf.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtxbefhrka.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtoftzqzdy.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmypndfaa.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtjiijlred.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtduegjkgp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtfalltwry.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtlxsvpghd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtnzbwzojj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtfobqqlww.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtkdgfwwhw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gthovivxpy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiodwvle.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtywgmmzna.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtvwoeoumd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gthgrsouoi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtuxuioxqg.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gttwrexgjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtxcsxlumc.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtziziwwwj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjcoijgs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtvicwumgb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtfxyaoknn.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtfpuytpze.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtoyowroyl.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtisbtqwus.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtxmtooouv.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtucaguoal.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtvzzurqpd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtvevcsuuc.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtdldxzvnn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtbwjjnnci.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtcpdltfsl.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtglqatflr.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwwmpwsz.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtmxgallli.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtzyslodqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtznotpnem.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtpeuxusrb.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtozhihfhm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtmtfyobsq.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtmodmjlst.html


<!-- 参考信息 -->