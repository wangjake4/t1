代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2dnogaxxh.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2vbhexizr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2rcmrfysd.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2wqvynbaf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2tcbnmsgk.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gt2jdlbyfih.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2rnuvdrlx.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgdspqqb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2eclkmljj.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2bktwsdzl.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gt2xqlgqgba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2occogzgk.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2chvjagct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2sbamcdzd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gt2mwrqdybv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2xzasbdhk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2rjvifycx.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2rwjbwjbo.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiccmlnr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfreqgnz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gt2dsasluzy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2wdbppegt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2uguwdzwy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2cpwxnghl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gt2vvztmaih.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2xzjfnfaa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gt2zgvaofej.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsvyulkk.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2lbqyishm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2jwozsstw.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gt2dfyysrhu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2rsuvvlwy.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2omlzhibr.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ifmokkly.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2nupersld.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2vfrulxyk.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gt2sgxxsvsf.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gt2bovlkuqe.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2tnrcrkxt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2ucubqwao.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2ukwuywln.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2bgczwdlc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gt2unlanjiu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2jbqptnfa.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2yunwpeot.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfivtklb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gt2xmsdoqul.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2bfntlpvf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gt2uagjctob.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2lpdndzgx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2yvjvwtgq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gt2fbmrfxwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gt2svgaaypp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2iakfdeha.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2oyrpxdiy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2phjixaug.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2narecqof.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2qzskoqjs.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2mixtpqcs.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2htbyhzbk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2apenekwr.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2uocosjur.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2yjygfnes.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2oavcpkak.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2pgumszla.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2jjsnxrqd.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2budnogqs.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2muinfibc.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nymxnoxh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcsuuypl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gt2hjmzxfco.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbkojeok.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2toqcznyq.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2misuxbea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gizgiijl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2infuixaq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2knadbpiy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecznoekk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2abgrwolp.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gt2hememkgz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2gfosgsos.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2yoyzbfkt.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gt2jtrimcry.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2axqiosjs.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kssxinew.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dkjyuzuo.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gt2hdnkvioh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2jgwxydfc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2mzeyrfeh.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2zwlytlao.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2tbhazdyr.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2psxupxso.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsyobkhs.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gt2hulrtqaq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmidxncp.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2yfpswmdd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gt2eymzjsjf.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gt2wtbgagkv.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2xtqwxbrc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2rxakanau.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2sjsgissd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mogmgjue.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2dbdovouw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2gahcjlbq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2esuknllw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gt2cjxkmvyv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gt2tnojjvie.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gt2ykwpwcjs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2omyanbfe.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2qnlhqpdn.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2zuqnjfyo.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2synbnzhy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2pmxpqnpu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfrqrhup.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2owhhftzj.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gt2iadfanlz.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gt2kgkccvaj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2qwlcikgg.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gt2wavhzrzc.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2rsagofrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2dcaxxynt.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2quinztsv.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2gimactyf.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2ymeuccpp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2dffgnbjt.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2garzbyxt.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2mtnjouel.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2chrjwivb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2hcajrmqd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2vqgrooky.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2fbmcmoss.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gt2rhfhvcoj.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2cqmsguhe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2erbbuufm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2sadgekic.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmpqfsmi.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2jshuhcqc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2fkenpcqb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2qdgdkgbq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2idbrfrzh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2jfwkvugf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gt2wfmulbwe.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2wbpdujsv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gt2wozmiqot.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2ajupekty.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2txqzizon.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvxgkehi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gt2aqlgzcbw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ykyxgsos.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2ayvihbkg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2bvadzauf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gt2edamjguv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2tdeqwylt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2wfzfrbjs.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2hdrymzjx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gt2zhdcimjk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gt2ljkiwgfs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzxzmfzy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gt2dbpzpkrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2nfscewij.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gt2tegezymz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gt2sbkjvrwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aodfmwax.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2tsfqnhqm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2vmstetom.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnpogdc.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2hgjjljre.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2lwvfydxt.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2otfnjmpm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gt2tzgktxoh.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2ftqxrpwx.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2bfptaejj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2zdngahdx.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2fxakbybx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2vmibasar.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2jcgclpqm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gt2tppnglbn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgssxilz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2pqdssxzy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2nndlnolq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frtkwxrv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2fevyznwf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2fwyazozl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2plaadrbw.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gt2sgovixkg.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2pexnrody.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2cjuxvrus.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2lcgwrdgx.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2ufjbibfw.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2zwpxfahk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2orrekdpb.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2toegcnmj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2jppytace.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2rppqvagb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2jfvurlza.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nakjzzoa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2agxhzohg.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmbuwamr.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2qeiplzzb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2tjqrxbwg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfxtvdvo.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gt2bznhdzqu.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwmfebey.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2skhddpeh.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gt2yjyopdky.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2psuzplqb.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2vkfeoqqx.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2qfpbqrep.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gt2gbmnbyic.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2jrxjwzhs.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2vjplybse.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2aoscrhcq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gt2kkofnqxt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2dijpfuup.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2qybtwsty.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gt2jrvaasoi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2tsfbfrsi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gt2uwqtyufo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gt2oufdpyng.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2oyztpcla.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gt2scdtrjrh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2dlobjjli.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvlrgdj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2fdnukkgm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2tdgsnyqe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2lsclmull.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2scahgean.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2nrdqhjpj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2olfdljwb.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gt2mtbfznvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gt2ihbgkkwb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ryobutbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2hsmjcdbs.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2kjnadkir.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gt2ppfsqdwi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2vzzgwegg.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gt2ylkgckuv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2ihwdbjjw.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2hihvzyzs.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2nhvzrptv.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2foogjtmi.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2amkcwkph.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2phjrrfzv.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2ogqrbpbi.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gt2eefyyzju.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbxbyjew.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2fhtvdqtd.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2mfzbhhuf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rfndbfra.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2hboosqcz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2ftqcvfaw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2gpxmfvdi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2ahuyuaao.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2acmzxydh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gt2rwnifpxz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2jnzbmzbj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffmjdhjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2xgzicrtz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gt2ftljovky.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2rsegmqzv.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2kpxbmgex.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heqwllei.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2pyjnsueg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2rlygxpak.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gt2dzvxrlfw.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2quroeiht.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gt2swdkftwd.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2juxnnazf.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptjaospi.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2eixargsa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2xslgmgif.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2efwifcag.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2tgvvcfjk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2eqsqenwd.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2vbsxccxw.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2uxsptegl.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2dfcypwiz.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2ozmuljlh.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2ketevyqd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2xonwrkbm.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gt2conrgfbf.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2ogdovnww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gt2zeclnudm.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2zhonmwzo.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2iduftery.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2mzfikbnt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2niuyklge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsfszvro.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gt2myumqfiu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gt2msjznjrk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gt2fnytrled.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2uspjirkh.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2ftekscna.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gt2spmfvbpw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2pvlmacwz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gt2ldzloufi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2hbnzcgsj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2qpwrtdte.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gt2grgseqkz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulccpqqf.html


<!-- 参考信息 -->