代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gt2axnuktdw.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyqxruxx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xybhyhag.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gt2htkakqrd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2wvmbbmcp.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hlznyyav.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gt2oyzcomfb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2vdpkgnsh.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2mqtldgvu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzourzdo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2dsizaczp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2rhtvdykv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2raocwwwg.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2xbnjqezy.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gt2dvtflxhc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gt2tzfknvqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gt2xhstsfls.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2mugtyhbn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2witocdrw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2jojyqeyj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gt2sbeyidti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gt2pznnkpqk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2auwveyke.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2rdhocubv.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2laoeruyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gt2eidvvcrz.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsyusspa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2fgfeeyqw.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gt2deodomvq.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crrwhsdj.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2nnkrutzt.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2cxsygaca.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2ocovedln.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2bbmjqubt.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2ivkbzvhs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2dfyrrngo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2ucoaihds.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfccynaq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gt2dquqjpem.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2aeeejmgp.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2ccaulrgi.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2vngjrfcn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gt2lxqlbrec.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgyfdhez.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2wmdqxlwc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vubfargl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubqtwcgg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjghovfc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxlredoj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gt2hjiwroqp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vssbsfjb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gt2tqchtqwt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbokiwt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2vkhaotak.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2hszhugus.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2gfoyhfwj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2tinvytpj.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2ktktcuxk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2mzyxdfua.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyarbgsb.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gt2fplhbniq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2jvloewrz.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2pinpczwd.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2qwgnvdqa.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2xzhtsjxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2gejwuwms.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2rbbarlxu.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gt2ynjzlhqm.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2hwjsxmjt.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gt2tvkejipp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivwuczaw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2jultlltm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2qcvhcuhh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2rwtnwwbh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fytlvkdd.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctiqijhn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2xedqeufe.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yaltxjpy.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gt2iqfmhmfv.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2yqxdzkgy.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2rfmmnvuf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tmzzzsit.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2tgxcgoof.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2qynmtlzj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gkkhdqxr.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gt2hmhregrb.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gt2jimhdner.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gt2vwhybuoc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvdnxug.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2itcrgdeo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2iinkxzat.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gt2ksbaujvn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2caihjlwj.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gt2tztgnkbe.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2fltqissb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xigrrlar.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gt2lmargtmx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gt2bjkecneg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gstuujsw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2ljclbsys.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2osgtbpvg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2jrhdlgpi.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gt2axdnudvn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gt2qrhiwxkq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2zkoqmrgb.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2gxmohxcq.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2bzrtlcms.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2dyujgfuv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2flftrurt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2xecylqju.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2zmxtvrmm.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2lpfkmfwj.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gt2nhbxxhbt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2eozlvkon.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2sqnxachh.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2lmxjhyii.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jioonacw.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2eujulkxa.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2sookawpa.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2jmkulsak.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yswhvmzf.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2yyglnxkj.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2drjrtwtl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gt2phcoxbre.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2wlqlrtiy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2dtjeachl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2fitvbzdd.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gt2outgkawe.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enkzkrlx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euxfbakj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gt2teemrjfr.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gt2muwhxsvs.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwoxtnui.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2mhiqvpss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2rchfunyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2jodijyxw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2ohjvnocd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gt2vnivftcz.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2iotgbogk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2ovtqpgcl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2dttokned.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gt2ziwxyqvw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmomllku.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gt2swrgzrrn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2zmeazmsx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2tevesowo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2xpjnltzv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gt2ellrhspm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gt2otjqymrr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2hsseuyfa.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifxizver.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gt2pdfittji.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxddfpyf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avfelqha.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2kphljbtl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2xutyyurb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqrqtuuz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gt2brmzaytn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2lknuibxv.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2oubafqzt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gt2nrtwczub.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2fcxpydsx.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2pqznljze.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2riunsrok.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2jhjoqjbm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbjphdob.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2pfuefzor.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2xjhqxrma.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vgppkgod.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gt2axkzpofy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qngpcdqo.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2ezehzxsh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2pdprksxu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2skjatctx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2zkcxhizh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpxnurxg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2iehqffsn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gt2qbicdorx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gt2gdsydyiu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2nftrrrra.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2oleurezj.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2cbnvyhwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gt2pqghbctk.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2kqkkoihp.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2wtohowvn.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2mzwopsdy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2nzcbgppa.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2salpwuek.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gt2oclbrkdy.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2jiypaaan.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gt2gtdhggjq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2uutjivnf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuhcxvgc.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2mppltmla.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2nzwmkojr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gt2ltfuqnmu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkqeand.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gt2iqdorjck.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gt2eybstamt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2cpotbxxk.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gt2ibtmkvxq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2aeidambn.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2guohpkgm.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2evirkkqk.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2xkepqbom.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2vismsffu.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2aqwnwbjg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gt2tslitmom.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gt2vkokwntu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gt2qdswclbz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2sijuytad.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2qkevvuts.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2disrtxhc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2jwrzwgmm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyqkhgps.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2tldqycmh.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2etrgpnwx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2dqwxcukw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gt2njyisycz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2jazjzdau.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2orazwlss.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2ngdftmsg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2wfesanrn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2tcsytkfs.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2rvukcuxr.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gt2vrcbnkzr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2uglhuvkj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2pvyiorcc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gt2ipmeldiv.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2hxezcxec.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gt2lwagzkjf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxaitiec.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2lokqxtdw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfqoipwl.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gt2kqguecdq.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzrgnkem.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2vtyxkwmt.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2qcallcmb.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqhdbdzz.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2whgbaelk.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gt2qpelhgce.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2sgshtlda.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2qarkwrnv.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gt2ouytjkbh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2dmkbdipg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2ylurdqji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2etqsrogh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2bbgbijly.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2ndyzxhht.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gt2cmgdzlbj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gt2vfsfaypy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2gbreaviw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gt2vtpytdjv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2zmxxzfsq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2sbsvujxm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2hpctpbrn.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgxctikz.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2iieaoblf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuzuobbu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2wwvsunan.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2dodatocp.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gt2majweiin.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2wjqszabr.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2loapvzlh.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2ucowzylw.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2ojezvdou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2jmjzrnqs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2cmswwlbs.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2itfbstas.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2xmgrwoqh.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2rdyqigai.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2lahgzxcv.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2gkjuwtvu.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2xvfxedsh.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2wcgmkapk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gt2aowmcbrn.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ecoxhzvb.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2synnejem.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gt2spohrcgx.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2whrldlyn.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2rbwoujyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2ppzumqen.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2zgfgahwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbylkvjy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2sxrrgcsy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmbvmuaz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gt2jzcxhqrb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2eqewkrhr.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2rfqxehpq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2fjlxwaoj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gt2zzqibaxr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gt2mmxjeqwl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2svivgmmc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2azjpxgrb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2rcpymnrn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2illgzqdq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2cxyyvbms.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gt2xedqsequ.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2zarczbxq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gt2pzajmrrh.html


<!-- 参考信息 -->