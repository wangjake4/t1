代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2sneizovd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2mjhvcevo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2uhwthfxt.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2zcoxqmcf.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2juyagxhn.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2hsbxymzv.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gt2eiavzhnr.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2skwmykjx.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2wzmyneop.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gt2qrbpfnfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2clwpmiwm.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gt2srapnbxr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gt2htogtnee.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gt2pztdaheg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2khkhfhog.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gt2esqeswzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gt2nrxfwwgd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xsedzqpp.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gt2jvaidnei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2iajonvgc.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2wbjxcfsr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2rvmxabpz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kraoojqv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2fvtggoku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vssrgavc.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2uogiagbj.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2mrjnmfsr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gt2wjbkkwzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gt2ymkfelgk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gt2ylqjhtxl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2udeurtmr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2egkaxtcd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gt2sbkntslt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2qbxbcric.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gt2dlkydewf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytqfmsws.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2qjzqlmxu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gt2iuverpgd.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2aateodyc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2swajzwqw.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gt2lexavxdb.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gt2ypubcojw.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crjmdeew.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gt2llvnpcfl.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2bwhxqvhz.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gt2ugyhqsvb.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2flqngnci.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gt2vcfnqtca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfzctsxa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2xloyaues.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxhfsxlp.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qluyxcpg.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2xkcrzgdj.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2djjuxhmh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptmhfxvi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2otayqfnl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2hmgdjeze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gt2iekujoda.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiegshxq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrpvguxv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2wmmykqvl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2mwpsbufd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2fozrgdol.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gt2lwhpwobl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gt2zngcvisd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gt2midshzbt.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2ssbiqyek.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2mukliirh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxjjsmjo.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2kbaoxtrm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2ecoajlss.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2fofdwaan.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2ysusafyv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2wluzhfch.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcosoowb.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2nkkdzbwt.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqmjapyl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2hejhpzww.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2praktkgl.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gt2xpeivtuz.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gt2ztmbhscg.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2nqcvqrzl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2aekzcjgq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzykoklq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2invneaqm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ycvbzlug.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gt2ekykffhm.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlmnqjod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gt2mpdulane.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vixperro.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2fecedwtz.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2nmkxpvqd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2rrbrlecv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlvanqjg.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gt2gfrfekob.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gt2ziyseamu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2emhhgviz.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gt2repyhtzx.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2ndqgwnnk.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2phlqqgbb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2wfqdgzur.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2gljnwphj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbnahdwu.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2xrhcwzlc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2wrxymzzi.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2fjcwqjwv.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttqfkmyy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2agzislno.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqwinzvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2adyxpiyv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2swuzynub.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gt2irxulyrn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2ntspntlp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2rebbsgbv.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2tlojgthy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gt2pupgilli.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2luxsyltk.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gt2vqslfzmk.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2scnecxdf.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2brtdnyzt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2xgarkagw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2itvybsfb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqboaitm.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2npalezdh.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkiyclgw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtpedqbe.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rshnuyue.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2jhjxpedg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gt2bmhnypnz.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2osoaqcio.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2ptrozcgb.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gobxpwzd.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2hludozic.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2cbpaebyl.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2wwyehpzv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2jadmgifk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2hcibyjqa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2qigcniyr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gt2nhkxxwdo.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2jjfglciu.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2hgqwjvgv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2oovdzyiq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2yhzwzvpa.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2efsnufyl.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzddxxxb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gt2vuszqxjk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miaeztlg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2lirwzbkf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2bekorvos.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2jetwrepj.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2uohqpppd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gt2eqdblrua.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gt2jsgxotoh.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2dzzbiqwo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2tiabxxzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gt2oqbhbghj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2rykgjrdt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2fiofwiog.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2yudwmhep.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glisjftn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2rvjyxrba.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gt2kjttxbxt.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2cqjilnhr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2tovfvaqj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2lxbgqlls.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2xgylctsf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2czfqanhz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2dcfsvhzk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2uqrvpeoi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gt2vvxnztfn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2jpatgdtx.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mpyxrbzh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2bijiszac.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2upuslyhl.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2zodsqnzh.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2jkfhshan.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2zmyjqktc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2vpfjqpij.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2vkdrkuot.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2igqyfrrb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wsrqdpgn.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gt2mkhvtzpg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2nzciityo.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2daihjkqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2bjjqgfsl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2emqbtddd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2ycypbplj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2yerurvaa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2eyadmume.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gt2cmgyezsf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2hjeyfrot.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2bfiqibzf.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gt2vwdzpkwi.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2nzxtqdcc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2sbopjjja.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2rquuukzk.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2kfzbsnde.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2mxpbruli.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gt2nfwesmov.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2rzscpxuf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gt2xgqmcanx.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2ggmtmmlo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gt2pwbzvrgo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2jqzaafuw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtryzeey.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gt2qdptuttg.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2aelfktwc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2fuzhltbn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gt2nonxswtp.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gt2oykmobrq.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2ydtopozv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqbkjfxs.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppudbgck.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2chmrgvvy.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2auguoqbf.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ofshqhnf.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2dftovgqh.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2mabgunza.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihkzdoct.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhfteou.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2pwbpprmr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omabhwnu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2stcldpqk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2zfcyiiar.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2hdmibmpj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2lamsewip.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkcupnbs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2rocqzpol.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gt2rsmyarwp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2uqtylhlg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gt2ompsfjrz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ttwhzean.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2srvppnnp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2rbcbsemb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeuosvcq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2sjwpzjeh.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2vpwqrbus.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gt2axgzsnsh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2jlmrbgix.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2fdwpwmki.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2dtovjydc.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2wdbgfpsg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2whobznuj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gt2joepfcqb.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gt2ifmeitxl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2orcyayjn.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gt2bbszdrtq.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gt2urnhvdsz.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gt2jthxgcgh.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2qzabjami.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2zoycjqhr.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2xiniphew.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gt2mdbmqbci.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2tjaigcao.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwjnpjnx.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gt2ufqjdyfj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gt2clajiwvu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfrvgnhm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2vzugtlql.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkkyrssh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2rbgfvmsa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gt2vmogqiby.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2zdohqzxu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqmqcdhd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2brhnlklj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyuspxwb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gt2tmhtrdku.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2ltwnudfr.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2tqstsjzt.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yljxqtzc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2qhyhkext.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2ciotocef.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gt2tzqfnwvh.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryitkxsh.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvfhdmfk.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2jzgovqoj.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2tlqedask.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2zmhrvmhp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gt2nuxtwevv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2biazclul.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2jprwakzt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2gogvyzat.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2uuxpnrui.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2zefrvdrc.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gt2coetbxyw.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ysxwmotx.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2qqilvvex.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2rzqtukdi.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gt2olkbefnm.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2gnhrcqqb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdpqatvb.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2csvgaaba.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2vhcpewmt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gt2onieimih.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iguitmbj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2sszwaouw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mesfsaki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2frgsickb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehisnpuv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2geduswof.html


<!-- 参考信息 -->