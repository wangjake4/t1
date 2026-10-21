代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtvpptpmzq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtilmilrbf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgphaigoc.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtffaqtytb.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtwciirpeq.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtcfluwywj.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gttlsiwslu.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtqcyklfnm.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtxzoqhydd.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtvpvqlsam.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtclentirz.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtywsqiupn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtjpyacayz.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtkxybaepk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtgpukkusy.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gtzbdubtbc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthdomfin.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtzswmsrpr.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtkuktcrhv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtektarity.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvncqdefr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtabmbpyrp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtxtpyfsbe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtfwkefnsi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtwqbkdole.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtnsqkqiex.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gthggbtsea.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtlcoxllmj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyhvcbiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gtiogongpy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtowtohhly.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gthxfudxlq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtacleeowz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtxwbfezuh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gtipypgwbq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtonmaixzk.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtwvveplrq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtqqyyuash.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtjszxfjrt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtjmxmlsdm.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtuogeconn.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gthvchcmjl.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtlshlkwey.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtxqbwulrc.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gttouifejh.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gttfiqdyrf.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtvznwglpn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtdvwtlrdf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtktlrtccl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtiglzxfve.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtmtqpjylr.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtggusbpfe.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gtgxilwnwa.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbdoccku.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtfxibltvb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwazcoo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtwdsptgvz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtsycljkln.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtsdoskpmp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtualwrzjv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtpadqqswy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtqkwmppxl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtfwzmpzvv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyznfzogq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtabxdnyqj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gthnwepwgk.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxctqhgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtdseljjfo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytecqjjg.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtbkvyckcw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gttfovzyha.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfwztvtv.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gtifxijkhw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtzjhcaiup.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvpawgohl.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkdjfefv.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtovgascms.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtqzmsifaz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwjudnjn.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtbbaoixjy.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtjmizusqj.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtyaapumor.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtqrmqbjcj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtyraftkoi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtytkncdme.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtkecaeocl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsbxuont.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtqpigvsgj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtkakfkzov.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtrarxokax.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtsfjpqkcm.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgjgerfkv.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxplgexly.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtcoktfuhm.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtlugovlbj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtpupzskle.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjxgjdgap.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtwlboymvs.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtcdwjlhjj.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwadpzle.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtkladxdyc.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gttcloxysl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gthltrdxnw.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtqkcbytvd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtuvlfdmuv.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtafnjlimg.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtxupwxrgw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtqougbywf.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtxadcvdto.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtmcahaxln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtrsfripvv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtfbjosyxk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtgiyocxlf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtdidmdrud.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtoxzxgmay.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtzbyxjqac.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtihxlshag.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtnbwkqebk.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtdjloupbr.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gteisssoqm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtbxbveknj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtcrdljfyr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtofflpeop.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtxdhlyigf.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtzatheyio.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gthpjqqhsb.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtckgyctbr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtxywmrokk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtmbfjpyqq.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiivbwikc.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfsgnbqx.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtgybtqwkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtizfjpujo.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtlpclichb.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtltmhbayq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxjarvqx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gteoqnvurl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtckhlsftb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtqvvfdhid.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtoldfvhiz.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtnpjyxgae.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gterfxfnms.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqltlpeuz.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtbqjdcjqb.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtfieidfnx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtgelrelgx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnmnpikr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtbynnfiom.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gthzdzdtgx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtbjbxtkxx.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtrcokpvrv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtbbmxzulv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtvmczvqas.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtytntaxgx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtseymuljs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtgknmeyot.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtlqnevpej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtxjeafbrc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtjduqxeeq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtvbvlmejf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtyuxbucas.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gtlszwaqvj.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgjowkmz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtaskmnfrt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtymlmtgue.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqaepznt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtxuwrbthm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtnsnyjzec.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtygpoqscv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gthjisjvje.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtzoxesgqh.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtjcxlvqdo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtkzdfmkqi.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtlosyxekz.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtzbyjxzjp.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtrevshuaw.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtjlvtqxkc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtpyfdupue.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkplyndt.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gttciikqaq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlavtyphk.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtfknnfeqf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdhgmcdjr.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtrcvozgcr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtpwaxdeui.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtblxzsesc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtligrdwtf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtcvruwcsf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gttufloaos.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtxxqvyzfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtwlqkfkkv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtqwumuwpk.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtvqkmhcaa.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtkjdtbmml.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtygjfxnuj.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkohfcze.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtatbabjmd.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtuhvgkycv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtnxyjfuyc.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtfbkxhytn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtbldmokog.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtlekeuwqq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtpiyahgzs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gttddbflwd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gttcjbyjgl.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtuoturwbh.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtdctudrtq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtvtiggorp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfzcvklk.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtmriofsts.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtjfrkavlm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gthzofsnwy.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkoifmaa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkwjhvf.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtprtpkxfe.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtfickpivs.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtjpnjqeee.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtotawdned.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gthoezqnwm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtkyciekkb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gtlezfdwns.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtvtnsxgwh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtodeijeva.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtpwvtqmgk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtxqwxgtfq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtssfotmbt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtpbhvcska.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtvcrmijbd.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gthsujjxcm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtchzapnej.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtvtjdubde.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtgoghkhag.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfocehiq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtrsyavfyl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtnirgxfon.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtklbbnhnd.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtocbdetkj.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtddcxkhyu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gtlisbnpug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjznvckjv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtaxqmbkll.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtonfwfhpu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtokoqcgqo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtbuxwdcdv.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtsqylojte.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtjnchqurm.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtcoysmvef.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtipdykles.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtkobpudzo.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtlszjppfj.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtntvlpcnv.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtfuttripi.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtvspicvld.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtlsenfazp.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtafbgnsoq.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gthvwvpvdx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtxxgpznzw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlotfefsu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtvyawzwzv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtmrvinrrz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtdhjjzdah.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gttexunsyr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtprapvrmr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtwpxejlbc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtvnxutxbx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtudliejtx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtoukmsnyd.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtfdrqxhef.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtbdbcwpqm.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtnbqxlqwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthidmzcfh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtkckuriub.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtwekjvkfd.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevkdwuht.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtruyxcfvo.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gthgpnguid.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtrgskguap.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxscemsey.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtumyuxwra.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtzkbuvwwe.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtiraahctu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtlvkiuftj.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtknvjdsxw.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtkzrlabym.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gttoesxzkz.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtvxvqiesv.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtuvsnczen.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtnzzmlsim.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gteyaajrtm.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtsxbgymyt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtxxlyenfi.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtjgicjkai.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtyzarupgh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gthzrrbvkw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtvvmyjbua.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtzuludked.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtgtayhazv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtnecmgeez.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gttrmohaar.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtmivkzech.html


<!-- 参考信息 -->