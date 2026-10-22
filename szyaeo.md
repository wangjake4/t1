代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2hzanwdcs.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gt2spchcmvh.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2wyrqozoo.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2seeyfqpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2dodubdtg.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2nejgzrgh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2dfjavcwe.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2cnmhurfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gt2vtkngcye.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2jfhhciaf.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gt2vracggfo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhreanws.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gt2jzsefpft.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2toadfkbt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gt2mbuibetv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2lvirknyq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2hlehjrld.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2fstnouig.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2utprvvob.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztnrktpk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gt2ztrpvhaw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2tafuhrcy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2dysnxqlt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2qbtyagcb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gt2zcgpnsaq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwaimtyt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gt2mguqchjp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gt2qgunulhk.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gt2mquhbptr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2wkiffsak.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ljwohdlw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2ujsmjwmw.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2johryeoz.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2btxxtgnp.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2tmkrmupi.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2aipoaojv.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2qjakkxxw.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2sjjtnkim.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2gekuoydp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2mqdtldti.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2mvraxudg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2oyosklwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2kbxkypdr.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2nfihccva.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tynnlunu.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2ccsgumbn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gt2pvigihlq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2iaxszaug.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gt2lcrgomzj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2oedqjcck.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2iouxoqww.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2bqlrmeqz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2cjamdouz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2tzvxrihc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2nbgpxmtb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2hpzsgdyd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2ojwlseym.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2fbconbxb.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhgvuxin.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jobuttxf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2jrjoyqtv.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2uectgnfw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2upnnkfgv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2pxoaqpyb.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gt2vdalvtme.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2jdtdohma.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2oszzuitp.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2pgjjefps.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2urvlvzus.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2ddupwkqf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vabmlzvg.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gt2ukbfpwev.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2pdztacfv.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gt2uuymrgtd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2gahosybh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2jmdpjwib.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2stkbcyoa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gptykmdo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gt2yyhlxthr.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gt2uuqjvpni.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2goeegciz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqmixqgj.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2ponjbfqj.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2akugtoli.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2orwdelcm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2lgzibrmp.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2yjrvxswv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2qacplnhz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2fptsirye.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2xheaswbb.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gt2phwllpkx.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2woqwosfb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkokaugk.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnllyfxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylmoiocf.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2mxskbgyv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2qsgcazxy.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gt2lijxtetp.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2fxokefsv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2zmabccmb.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2mjjwnwub.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2igiodulp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gt2wikcqgag.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2tkfxixvh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2lqmlvsqv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2akeeemli.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2yjytfacl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2atsdjwhu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gt2rogupnww.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2mwgdbsux.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2sovvzsqn.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2bfppcejw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2cerujeif.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2zbvolqmb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2rjcmniph.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2lhiizfxa.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2mtuchapd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2jokvqpam.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvbpfav.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2xnewujsw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2tfvpvvvh.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2fayojxwl.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2bbtpyohr.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2vlhfkreh.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2wmdgpdck.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxqzlslo.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2jrwnjicz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gt2pcmqsmir.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2cznjmnuq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2swyduorg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gt2mabrbyoc.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gt2wdgaumgj.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2sofxygek.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2jbsyldqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gt2hctjilts.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2qmuwygin.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2bfeszora.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2nwgpmohg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzstifue.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2hfawfkiz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2rbxjpffn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsczfauv.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2mgaxzxjo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2nswebuee.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2wyzntrde.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2fkmfeweu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2sjgxdpvw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hscydanh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2bomfjaof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2xgyzeoqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2azdgqhen.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2vffkjgev.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2eopbfpkz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2havxlwsa.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wddvzrtr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2liepyntt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2ardmvxqo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2yslkpcog.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjryutyy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szllxdag.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldjagpjo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gt2lhbcnndm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2clkuozxh.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2dthsaisn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2nukwolkh.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2ywgrsupo.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2sqdqxwhn.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2wkztbuka.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2lfejghkb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2zoexmank.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2uygivtky.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2nlrefcyi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gticyfkh.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhjrlxqr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qxxlvmwm.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obrbjxrb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gt2hofdzyoz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gt2qdqrkuvs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2luyozojz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2accaedxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2mrylyjmc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2tfljakwa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyxqdwpi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2peoixkyl.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2uzceagcz.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2kyydtofy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2inrksbhc.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2cdupdkto.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2vynjsfnk.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2idaqgvdm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2jcyshfjc.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2oyytaxzq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gt2towgssfd.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2unlgdwgf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ymraniav.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdzyhrnd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2zfrspupk.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2ysaatzle.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2fotagcpt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2pwcxsdxx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gt2eysjjmyf.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gt2oyymtvfx.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2ecwjbnlo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2rmauzazg.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2rjyvttnc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2lbekhjku.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2wjdqrrrq.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2pizzmlkt.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkcqtoct.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyfftuoq.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2fddpyeov.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gt2chxwfpqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2rhhlkxnu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2ozusdtsm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2ejbpqxnx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2hexwhshx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2wkvdtdpt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zilqkcmw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jamwifip.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2stebbcmp.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2wjfhdlgw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tdxsjcbr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gt2hlhhlaks.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2jgpyxbxt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2gifpvjlp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2rbwxysvb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2tqpjtvuu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2uzhqkcbj.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2wdaevowe.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjvvrngk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyjytlgk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zoywvgge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2oeihxecd.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2ftxtbkvo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gt2mcavsdhm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywlqnase.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzmkecok.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2ujpbbcme.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gt2ufayahim.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2dcjuqvvj.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2cudpzesd.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2qrhxtvup.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2nodkuxfv.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2aexhrgtk.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2evnhmken.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yahfhtjh.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2jljbztng.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gt2nysnytsx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gt2wnqzkkex.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2ltykklqi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2qnbrjxmj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2vmtxnxgt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2auqwkwel.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gt2mdpwfulp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2fyqkxzom.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2wivoatni.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2xwyyfzpv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2wmbuhnfh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gt2ceioxvxl.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2azkvclmr.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2livsljgi.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2wkmsfriw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndichios.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2jviwisvi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njlohzrh.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gt2mgtlcogp.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2cfaazddb.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byquapoy.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2mqwqdaks.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hocmttoo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gt2cgpjowvj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjjwduye.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gt2syvbiqks.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2yuytukqh.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2dyepfbjw.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ydtqxchy.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2phtfdzvb.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2snrcazdg.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2nbisfcfl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xclggvkg.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gt2jjuishga.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2tnuxexir.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2yusjlzuu.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gt2vvhylecq.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2rtooapyc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niyjvlwf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2mtzezpsy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2rfvgddjm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2ubestvcx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2rzxwpfxe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gt2luzctotz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2frgsanla.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2nztwcbax.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gt2iaqvqigp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2bxhfbqro.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gt2gqznrojy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2wfmbmgfc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2pozckhcm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2evqrmwfr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2atbbparj.html


<!-- 参考信息 -->