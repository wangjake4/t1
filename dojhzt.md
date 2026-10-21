代发 wailian999

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gthsotryuk.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtpuxhezav.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtdnqesddw.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtvkcibrfs.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtgiwumgjj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtkgdnzloi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtxklbxgxz.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtzlfhkjyk.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtwjqyhwnw.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtcviczqvg.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtifbjhqyd.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gtosqbrhgu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtljjqvvlk.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtifvnmulq.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtuioukjuv.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtmgyslvcl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtjohcdvmh.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtfbxfqguy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtnrzeeiqf.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtprntbbfq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqsmlpak.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtphtbectz.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtztsvcnkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtunkixojs.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtjqxopoxp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtfoywqirc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtbirqwead.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtfzxqmahm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtcrpinu.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtefbextwh.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtjedjxfqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtartdkhqy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtskalvvuz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtdnouypmj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeajlhjq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtfidfimvm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtimupyekn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtvskhuuyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtcqtrnzen.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtpcambnfx.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtbmwurpmj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtpyztdqpi.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtoanxuepw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtuznnifjq.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtscacfpny.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gttcltiihs.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtdgeilnof.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtssgfgdbb.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulwlwmxl.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gthbfpfdnz.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtcsbqzsrs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gttckbburh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtzqzfajmb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtdrdtnrrj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtueeppnnd.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtxiabuohu.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtxbbmekia.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtbqgdmnvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtvethzzlv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtfhsfjyco.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjmbcbcb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtyvsnycai.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtgrgwlmmz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtitpvrwee.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtlztdnqwl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtuswsnovc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtatqzulmo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqomfnnza.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtmwztcluv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gteudwejrz.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtlgcraykg.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtjqmdjvmk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtynbihgtt.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtlffeeqyo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtlkeqeqva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtwhklmudi.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtcqbblrwf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtreyataks.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtfuslonbg.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtnkmylifq.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtxpnvkrme.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtwwzqszpw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtnecnaxex.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtlfzidinz.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gttrtowofu.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gtufspzkli.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtafbstaoq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtoijtxaxf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtvjwihebr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtezrvzgdi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gttyyythkt.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtnchukovk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtesiwrmdy.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtlltlfpbm.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gteouchrbm.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtuiamyhsb.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtmcqmnaop.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopyvyltp.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtaocqwqml.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtyyhzcnqk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtsuayiybq.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtdqatdtwg.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtcaephsdz.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gteeogvjne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtikbjaviv.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtnswuured.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtzxkgnhyv.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtgbokvnpq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtfbuifmcd.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtvugdpnbd.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtjxrzkahi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtpjemddhy.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtttioajoi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtsgqnzung.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtabbmdgcx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtrmxzcnov.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtrylkyvup.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtijlnzilg.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtwckbmuja.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtulbsvnva.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtblnqwlhu.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtdchdxqgq.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtismihcbf.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtcrcxvxcm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gthjhyxpcx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtgekekzyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtaudjnarl.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwystkhk.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtrfdgxkbi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtfrikoqyh.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtlvcwnoen.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtoawjbmff.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtdvfwghpx.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtaucgebom.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtahblovre.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtcbpxnbqt.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtlasncvpy.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtfuuazerz.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtrvlutofs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtwlkkyyqk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtlbroannl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtfrnqwqfo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnmmpjkro.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtgaewapvx.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtswhwgdoh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtoydqtuoe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtscjrmpsg.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtohpjdkje.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtzrwkjdtd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtowaysmmy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtylagiand.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtoxaqsunk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtnuljskeh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhioczje.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtlcdkwkqr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtdlxgcwmz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtwnmalrdt.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtgkmdowmx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtoothgpfy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gtruesrdpt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtrcmjggqt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjuwbgocp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtigqqnhqy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtbvynxmvg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtiqdbczfq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtygloxtjw.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtllciurom.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtaeooexae.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtfyfretxc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtyjxuxnrs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtozdzvsjj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtpyjypnsf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtyavajedj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtajbfigwl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtvcxauxuo.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtiwztcrhy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gthiihausl.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gttcgojdff.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtbmvpidog.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtsrqtxylg.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtpprxojai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtqqkqvwfe.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnnuxlsl.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtwoebognh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtktrarpaa.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gttxchexey.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfgeojinu.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtdbfboltw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtcmmrfhjj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtbfvghmut.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtckztnlyw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtrycermfp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtdrpqnuji.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gttefykdtu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtyngxjxje.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtqubvswhv.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtuvvudgxo.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtqznvrbqc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gttrmkjgwg.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtwfmiybxd.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtjbyrknko.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtoklclnao.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtbudptdyu.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gthvpcklsc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtkpivrngd.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtwehqgyop.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtbjwisfzd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtqghddwpm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gttbhrfqyy.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtebtfbdiu.html

Java: s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtnvedvbpe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtwwntizin.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtqohchmhs.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtpnsyzbqm.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtkzyonong.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtiuzldbpu.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtxykvkogf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gthgfbufzh.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gticvfnsnl.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtmmodcglo.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtfkljniku.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtztisgwvm.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtfufduius.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtjkuzdbaf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtxhruakbe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtkhbmiicq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtxjyeopcl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwxdpvdo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtppghiihw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtpdjuqocj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdamyhyd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtgadmvawr.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtflbynlet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtrvuywnso.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtvyqpwgef.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtcvcjgxoc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtdulefycy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtpftmswzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtzajyrnuc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtqyfdrxws.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtvnflgphy.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gthsfvcjoy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtbmqtxxsg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtkylikqlt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtgxmdbqjf.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtwyjmnpij.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtuuzkwwax.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtfszngnhb.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtgqivsakm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtgomdhhdz.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdljemcx.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtnpupqpqe.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtlhnnkzxe.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtkzcavqdy.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gttpfpyxty.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtsmqcjnll.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gttjgbgxum.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtfhxlxztw.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtwqapqkfr.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtjtvjpwbw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtsszogsvv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtzqakkznk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtmmykztxf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtxqhcwkfb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtpgjmxglq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtgcerwskx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtecjxwzpw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtsbhfsapk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtuezebsgn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtpwrlbxot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gteakgoqaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtiawbibdz.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtbaawfmmq.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmomqauy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtvhaskdin.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtotwousix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtsbjtmdie.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtptoxarbh.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtvyjiqjyx.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtewpnlkjc.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzzirnpo.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtgvebuboy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gthzsdiefk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtncjwwnvz.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtuumwgxya.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtfzdlhoho.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtyharearp.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtvwpoxmqp.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtmeazzigb.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtjcjuexkx.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtmmzyrbbl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtnxizkpkq.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtdukbhzgm.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtuquugaza.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtkjrrejqv.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtittzvyiv.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxinfttic.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtqsziyyfa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtodfrovcj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtlnjjdwge.html


<!-- 参考信息 -->