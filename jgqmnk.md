代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2slzmgqjr.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2vzteznex.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2ehjrrqrn.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gt2jvzmptvh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2sxpdlqno.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2xpbqtbaz.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkilzdba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2oopytuxs.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2stswwznc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gt2afvkqafa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2hgksfiyc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gt2ovxwlrwo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ampanyuo.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2ycirzvrx.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2uqiaayfu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwsrrwpe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcyxhbif.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2ujeiflbr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2tddbjmom.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2prmntnmo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snavupgf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gt2urpvffqz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2jyhgcvsn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gt2boixrnnk.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2izhmgybn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2pusevijw.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2betrwibw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2llclibzo.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzahhcaf.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gt2kfsrgyog.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gt2rfmbpsls.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2wcjiuqew.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2mmdfuewg.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2ctheylvt.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2bucdilul.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2cduabjqv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2gallbswp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2joulfxup.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2ibicuffh.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2iembijmk.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gt2xdrgkofs.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gt2umhcddqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gt2reyxtcku.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsljbrnn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2kkcjplzf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgnrbpoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2unyikusz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2dskxikth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2cqgjgeio.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gt2dwdvdier.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2qebgbvgc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gt2koiqpmog.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2dhamvslk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2gkkrtynt.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2tudujoqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwearbgh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2zagatskp.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2yzywjezz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2fvsbqhgw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uohzmdtm.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2ywpqcogw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2pwefbsvm.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2bvjeilwd.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2osmorjmf.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2adpdpjqx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gt2xmjzvpho.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2mfmtifra.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2deeuoqek.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2kkyifohl.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gt2ephidapw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2bumivzks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2zjagkxkk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2benwxojo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2hyrmebrl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfinqfwo.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2ukpeerdf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2dvswvfqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2egbeciyy.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2mivadlrq.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrnoqsrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2fjczzyks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2qkotzolh.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gt2cverqcqd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gt2tczsketa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gt2pnncqwih.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2xpfhygte.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrdlmqwe.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2wjeyfjbr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2imnosftv.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2meiqyyso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roubdwsv.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gt2nfehoqcw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtitsprd.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2pdplvray.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2nqbnthxn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2omcpgkuh.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gt2ayglxsyo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2grlkoqjo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gt2fqssrabr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zftfjdjm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2wcnnkajw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2abrfegxl.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyzviwzn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gt2rgejljqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbwuqxjd.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gt2fswqdssj.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gt2bxiiymrf.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2byslswfe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msxhbhzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2svbalele.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gt2hdgolrir.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2baprxiav.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2frlkhcmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gt2drjncuyt.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2enjfatzo.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2hyqqqtqa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2dgybigyv.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gkglffjm.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2xzsugoap.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2egshtonl.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2lcwqogpl.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2kkytwjfo.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2gesmbxrp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2vqftcoxy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2cozdymrm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gt2gteozjwv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2uyirbqbb.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2yeryceth.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2gkntkoyd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2jvsyvnmu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gt2ioajuhxn.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gt2xcxivujm.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gt2adnenquo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2tgatouet.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2awyrewuz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2ltklxspm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2ispiszfr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2zepaktku.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2vqvfbird.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2eayexluo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylbclncr.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gt2fvivxqeq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2jwzndjzg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gt2piumadnt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2rpiotwlp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2ivmmvags.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gt2usbosger.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2cjfrhrep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gt2yalazhtr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2wzvrfagp.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2nayugymj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2mtxfymls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gt2sryknzap.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gt2klqofcae.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2tarzzcip.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2xbvovgtn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2doyvxcak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gt2txpoplks.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2tiniblyz.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2botrnqek.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxxbglmq.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2gsupvkkp.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2hufticxb.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2mkhamybx.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2ytrwgkzu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2pdkfrjbv.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2dztjcqzz.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2qfzuivmt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2uyrtromg.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2atxtghym.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2anshiamd.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifkqxupm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2vykobydl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2phopacig.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2mlpsiycd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2xgamomvm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2aqkxunll.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2cbnkxrnf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2dcwsrwnq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2virmoodn.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2ybxmhfay.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2gytgniuk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2eexeooik.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2oufniwxh.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2orjvvavb.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2dxihlcxg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gt2qimegvql.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2lpbcwpec.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2bblxtmsm.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2gxbmnhlp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gt2bjlotqpj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2baeyimfn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djbkyzcv.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2iwlifgsc.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2xuffnepn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2gqsksxbz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gt2cjtxrxlh.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gt2wfyihrve.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2tglnqgrq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2rofccltt.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2lqnljxzy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2bgniymzv.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2nrrambcz.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2xtbmrowm.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gt2zwqdmxzo.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2nbtyiqdx.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2dhzfryqm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gt2lwfecswo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2zfrzfixm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2mopwhyyz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2aiisepxr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2wwhdisul.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2trdhhoej.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2wbrihkpb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eakgmndm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2xsdhvdkr.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2lxgipkfa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2vdioqsja.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2ulvyrhao.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2lrmemhdn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2ezsxakdf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2oiacbivb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfrmndlp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2rplttuzs.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2yswvokko.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2vzaschtm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neekokjo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2xwlqiryy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2baprfsft.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytfvtqyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2lkmxwvsn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ekcxhmfl.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gt2joknsjjt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2acbywjks.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gt2crqjswkc.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2kscvifrn.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgrljmrp.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2kvqvmkjd.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2kyfsneed.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpwqtpci.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2obqqxnsw.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2dkykaofz.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2dldljcss.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2sdjdagrp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlmntehu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2hjwjxaxj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2wevgcqpv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2doghsueg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2juasdiwm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2jeensovp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2bpwoldph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2khxajydi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2nlqotnrk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2qqlifwmq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuryhpig.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2awmbxdqq.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2hyvuxksx.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2cvftcwje.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2ldxlcetj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2lwnakmav.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2qvcyxpfy.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2gjllmwyi.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2qbviiymd.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2nubayogr.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2vhhtgsxd.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2qtwkuuat.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2qbbnfytp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2qqxjcedl.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2ifeudlgo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2zqfgzrog.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2svmyabos.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmljqan.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2iaccjwpy.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2jmnulohn.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2iqzjdcax.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2biebkygg.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gt2lqlzjubc.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2rkbioieg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2ifefigyi.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gt2pqhugttn.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcdajbuq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2nlckdrxm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2vfkjymxn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2ilsjunnh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2jqqjawsg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2fnlfhdpm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2evlcsqbo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2obbseamj.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2aoxmfrse.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2bshpzhku.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2dlkybgsh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2tzwjdikt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2bmlwkqkj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2czonwgmg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gt2supnoqkl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gt2zaicjhmq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2yrgncrma.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gt2tlsvuzki.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gt2zznrvhcu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gt2hgdglfvd.html


<!-- 参考信息 -->