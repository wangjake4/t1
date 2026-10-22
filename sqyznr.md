代发 wailian999

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjlpzhxs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtuktvxwqw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtpptaeqmi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtewdcjpyg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtsvwmkvqw.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtjxgcprhq.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtgipjqyiz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gtckmenatj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtzieeqqcv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtyeqsvncc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtanajxzez.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtvfxxdqmy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtnxofijrb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gtjasfyqmf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtbupgrklr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtycsswltc.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtctywxyfh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtaxnmqito.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtenygcaxr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlewkopgv.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtulqblqsp.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtwbmsannl.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gtqoqvhaah.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtsuzcbzyo.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtcdkqxnsl.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtgwanqsdm.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtisxrwhpp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtfnvcncjo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtvupqwbnr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtuarmwwaf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtemttjekt.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtjcpdqhsr.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtlxeksggu.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtzozjivxg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtyquhnmmi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtyufdhskw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gtqqntszsx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtdresdkjh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtlktzuebf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtotsrhqen.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtsuqghkih.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtgcxvcpbj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmgfjavay.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhanlytq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtsbziegnu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtegnyuzoz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmkkjbsxu.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtezwxdnjj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtimteqevk.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gthwbkwpqf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtzyvmloxv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtiyulqyji.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtjcmobrfz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtsjnerfzb.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtczmuayqz.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtzqndqtpt.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtsjdgjqjf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtlcoqasat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkecyimvu.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasontwrw.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtixrwsqiy.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtdxtwzyxf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gteplywoww.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtfrokduou.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtovjiqqui.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoqulxqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtdizpcdhl.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtjajahgnk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtzthvvdsx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtxlylowyg.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtlqsqfvsc.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtrywijzit.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtadtlbljt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtywjfgkke.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttfbrsbpr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtueynozjc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtmasrksvv.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtojyyopvn.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtzcomzukc.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtvbdakflq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtzagpxary.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtvsnhsbfp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtxpdbiizc.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtthulcukk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtpkvfodcw.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtsazkknxd.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtnkrzhyyq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtmgnxpncw.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gturmwehcw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtwykrejts.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtjtdaocqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtoeuvitbb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtkxgpvzjz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtufauqros.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtdtdbgtcp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gtjrhstbmd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gteaagxtjx.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtelbffjlf.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtccxcckit.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gtxjunihqy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtjqiebwzw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtlysdqmsn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtehzykgde.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gttshlzznh.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtlsffcfqv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwblffkp.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsiakglf.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gttwnpjjif.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtzlvefksd.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtidpafnqq.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtlxolnfse.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtkoklhjea.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtjsxqjcuv.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gteinjjjqu.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtkyuewatb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtitfqlcaw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafvltqiz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjyrhby.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtkzyumjkr.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxrtupqy.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtasskudnz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtsflykskl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gthhuagsrr.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtffvnngqe.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtlvktkhii.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttumlqghe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtwjocuqxj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gthkbhbuea.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtfxiympzf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtwlfvtrlg.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtokcrsmmp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtsbvkugsy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtvzdrkirh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtlkvtfkzx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtsbfoxvcz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtxcpkplbb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtskkzuimg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtkfedzkvt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtnmdilgdc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gtquehfrhu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtvpxbybaw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtbkzshiqt.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtckfhkehb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtzhvzkant.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtvpanwefx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoecclmkk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtunhwkdio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtitniobxt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtjyrrqkcv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtlbmxdjxp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtgzzhyynw.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtdnfmgtps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtrsrnghys.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvugmawgk.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtggdyjkaw.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtucjmxlvh.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtfiptqueb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtiulfjcns.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtzwuinqzw.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtzurogfho.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsipfulyw.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtbjhzozyj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqxbstafb.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gtwfrjbrai.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtubfiamyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtxfviozxm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtypkyblhr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtixftigdy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtzfhsyvau.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbicmyss.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtndqlpqcb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtntcbkanc.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtalexoeym.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtdjdgnjrs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtmyyamjvx.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtawtwavtb.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtrfudmmgu.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtbqqsiogc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtdqwijdji.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtuqzqtkvh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtmxhghjsx.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtruzreagj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtituzimdz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtuhxybcme.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtaliiwnor.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtsylxroly.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gttsglgbks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtolomfbbh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtfavtcjvv.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtudjkwcmm.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtijyfpnjc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtacxkeajf.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtiijmfias.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gtckgapbbj.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzchqgbt.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtlplmownz.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtsithtmre.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gthcixsonl.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtlafukwzq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtlvqpvrjz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtnpcuyflb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtmwqwouxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtyfxestlf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gttzmovrog.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtumwumslc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtsufwmqse.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtkmozrqjb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtrygqrfcj.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtmpjcgqua.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvntgfms.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtmdssucoq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmxdvmnqh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtbhzbpelw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtapbosyac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxnvbtrsd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtgevmdyde.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtolwajaub.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtjeqqtxjm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtnrmwpuck.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtmqfmrbri.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtpcszzavn.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtlgftyiao.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtrndrbwws.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gttajwjryo.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtohztrqip.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtlziispof.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtjizixhib.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gtfsfdtakq.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtuypdufrd.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtrxrnfipz.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gttqccfyiu.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtrejsgooq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtrmtpckwv.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtabcjitlk.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtvbmswvnl.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtsvjmqtib.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtizthitef.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtxgjdeokf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtkeswdwvo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtzambdwmc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtivrcjjbp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtuuqobfuj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtahbhuiwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtadlqbayq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtzfpkfgim.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtoxsfehry.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtosleaovr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzfwatiem.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtfjqlgdkz.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtsrhnrdfl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtmthpeakt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtunujhvpc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtyxqkhsmg.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtqqdkjimk.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtqjrjzyzk.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtulurztfm.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbjmtrtva.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtqymjqxyy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtfmlcmmey.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtisttqooe.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtjkyzkfwp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtfdwmdtlu.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtqglfbekd.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gttvnjyfwf.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtzybsqzrp.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtpljqeqrg.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtaekogqed.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtkvivxlum.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtbmdysirw.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtozrzqbxj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtijtgwrip.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtgxodfrjy.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gthltfjnze.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtwkivvccc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtautqebxd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtexfkamnw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtsjwkiitd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gtyjektovn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtdltdrfdq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtlybvsxio.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaffcwrtk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqtdqjjv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtfkvsnydr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgzqqvsr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtfpnbrvrj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gttuxjqmqz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtfwnmuosw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtdcbigvch.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtjtayklnb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtqxtjacmr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzgpbqqb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gteiooletf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gthfwieksm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtbcizbime.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtajkhktnl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzxfhrteb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwnexgufk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtxtztoulr.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gttfzsanwp.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtfavatdpf.html


<!-- 参考信息 -->