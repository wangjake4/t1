代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2dmxlqxwp.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2ztuffkck.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gt2wzlyemyj.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2roaprgkf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2ihpaoiix.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2cmhjxmxm.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2lvhywtrx.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2xduhgsyd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2dpammzgt.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gt2fdnfkgmj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2munmsfxr.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2wnmpgfia.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gt2yqjmkvqw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2tqhgebtj.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkwpchwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gt2tgdaaavk.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gt2kdibcpao.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbbezpog.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkjfnxiy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gt2vuejxfzz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2iesnfqyo.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpxajkua.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2tsfybbtm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2wzzqocwn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2yxhkxwfa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2aqhgjkpq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2huunqxke.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2fcxdcorb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2whxfvill.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgdvqovr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2zmvlbqzu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2afqgmdim.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2eqibwhvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2pqjcjcdz.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2gzldmsge.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smvgqkxa.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2ykddcvei.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiasgzfo.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2fbtfcjnh.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2beknwgql.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2wfkvsvmm.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gt2bgrdatok.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gt2gvvnbzin.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xooiopvs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2kdqzjqod.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2iiefcvnh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gt2fwhcefdf.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ondqnucq.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2zxjndorj.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gt2cxdkupop.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wdzbaxbt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2sndsorby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2mdhauysa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2cpomgivn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2xuflnfje.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gt2twrfwkht.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2kyzxqlty.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2hatkmsut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2ygenglfw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2qrhmlxvs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gt2fhunawwk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2wqicfuwh.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2natrbudp.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2nfxntwtg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2esmtgvaq.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2xmhiadwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2lsuaeyqg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2tyonptgv.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djgsfocm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2wftifain.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2vkbvnyvw.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2kzkwbyyw.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2eitonrha.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2ikqzhyyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2zqrofncq.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2jmnosbmu.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2yxtzhruv.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gt2cpgwmpwz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2bixjzenj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2fgsabhgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2wmoapqij.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2ueqcwzsv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2ydajxxjf.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2woyymatz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2xmxjisxn.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2xbqceosk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmeonjr.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2kyihgqqr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2lzdajbzm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gt2lcspwxjg.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qszopwal.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gt2arxjfwvh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2fsdindmc.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2ntiuzuvf.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2phabwglm.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gt2uzxzcqtp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnrjokou.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2midhinpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gt2wfwdlqnf.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpekgvjv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfqnohwu.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2chhfjezm.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2smklcsuu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2yzgvetcl.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2vgsluwuz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2pfiwcclj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gt2zjwadhmj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bflyhrjx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2umdgpcwn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2kjvaodxt.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txvoqfpd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gt2fgvwsugh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2vexsqwjx.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2qxpyxaot.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2wucvzgln.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2wpskimoo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2skdoejni.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2gqloqijq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gt2ljwwcqwc.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gt2wxndtakv.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gt2jwvtpgjw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvytqump.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gt2clopicqg.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2ooxnohme.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2snehomwj.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2tojbqlpc.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2mjirlzdq.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2vgpzdyld.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujcharyk.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2bflqkmsh.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2wxclpvrd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvrwruxc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2qaqdyose.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2xuczsmlc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gt2cnewikyk.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gt2wgxuqsmn.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2tekvcnsx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msgkpxtv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2nuurkbkr.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjbxcdor.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2tadkdbdv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gt2qvhhhdss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2crybwims.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2gulgbrml.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gt2uhbtcsdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gt2ekjusqcv.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2usrwqing.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gt2izzaitql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2nuabzlsv.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqgjqbcs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2zkimtfas.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2sjgfwxgw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2kudtlajz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2mhipessb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2djrvmzri.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2uhjebfff.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2hsywavvl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2migfhhbo.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gt2uldujndt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ensxjdak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2pcrjtbbp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gt2lhytjrmq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayxrwagn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2iccsfomz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gt2hezqgjew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2klvaafay.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2hgmtebpl.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gt2ipogqlin.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2avvyelvt.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2uwvlmwgo.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2lxzbfyan.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2dmifmoxu.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2uvawxddz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2asibgjxw.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2awxuchmj.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2gzvpxxfr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vpojciqb.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gt2psqoykhw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fylwivhe.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ulfsopxj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2mdmpezkj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sovcwpft.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2gsppslyn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2eycghngm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoqqtyy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2dukaitle.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gt2nknscoxq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2rybmbcwc.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2wuuzasty.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2drupftfo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gt2hxjgvdjr.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2raczaidh.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2tbujyywa.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2zovxrjsr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2kfnewhxg.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2rljhitmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2ylqlppiv.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2hznfdmwp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2piirukoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2dqobjcae.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2quspqdgw.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2gnuovrga.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2zqspekai.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2rwkgjkrp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2vjhbpurk.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2cdnvcgmh.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2pytnugwu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2byeehcel.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gt2lrocbere.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gt2ohtdldmq.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2fwusnwjw.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2pkcgkdfh.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bifmgcit.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuskhhig.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2thihbakb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gt2dfitpjfg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2quywwaus.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2wfzolvzf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2eudmedeg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gt2ngmwixvq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2nicsmdkz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gt2rcvuynqh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gt2jjkzziqh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2wvmamvuw.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gt2txxbyqwg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cavgafaj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2qwodxgrp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsknrdkq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ekyeuvky.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2mxldnyxe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2nsmldnri.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2vkhyqrdh.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2omnlimdc.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gt2xuvhgooa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gt2swnvdjva.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2iutjlwaq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gt2pfkqabdn.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gt2gmoaodge.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2dqvlezwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ympjnkic.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gt2yxyjdtqj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2bbwrstae.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2ckdrqhhn.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgyeskhl.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gt2ofimoxvc.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2vewheyjz.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2gpnrivfu.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2luvsedmo.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2xmrlhbjo.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2gqflbloo.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2fjeuajmc.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gt2tywvyqct.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2dkfmioew.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2knsoqzas.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2zujxeigs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2nfjafukl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2kvvyvhtm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gt2ymfipnan.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2nmbnxtyi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2cestvqih.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmouepyb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2slmqaars.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gt2ultovwcu.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2ylsjpesg.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2katuzmur.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2xkpnipyv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2voshiymm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owtlvlcf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2ddtcebqh.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2frsfdixy.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2shugsyyw.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2hjsrcwsg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2ytojjrji.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2vorbbtgm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2wxawyyuq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gt2wpnjzhmr.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2eclycwsz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2ydxuijek.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2uwttqcjj.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2ypqhsilu.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2flszhfbw.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2ykiprbky.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2koaclrmk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gt2oqvwqpli.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffmldoke.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2rjkbbptw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkwgfcae.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2esnokosq.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2hfeweesd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gt2ecujqqtl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2mzgtokkx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2rihwutde.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wldpzqym.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bliiqxoi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gt2zzhbayau.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gt2ocudhlbd.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2ggapuktu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gt2rzsnvczc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2cuhqvvdb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2xmzlfoct.html


<!-- 参考信息 -->