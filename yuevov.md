代发 wailian999

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2taceynsy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2jgrtpwqc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gt2vhmojwbp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gt2nhpzqttd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2erofwpsn.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2kpopqekt.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gt2ocdfqoyp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gt2omtuxzea.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2qnivequa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2xfolrdwf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2cihygraf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2paizuafd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2owtfnnll.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2oxhzxlrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gt2ihzrzppb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2bueywohm.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gt2zlsknjip.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2anpvxqop.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gt2hykataue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygkvphte.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2azenqfyr.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2hxzpicjb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2togotjoq.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2gvcnpten.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2oonzwmzv.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gt2inlbrxuw.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzpgszgc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2jzmrtchd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2ukxwotwx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2nhkmreja.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gt2vahavakn.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2nkqbkbqh.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gt2ktezgunb.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrylzuon.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2wpnletab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2qqsaqnay.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2jfuwezyx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2ohgcoerk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2hfvfedjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2bfzaovvn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gt2qavpgegk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2cgmmslyn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2jyugnzys.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2wjqztgjz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2zcqqtncs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tuglkygq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2jcqhmdbe.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2cefcyahj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gt2rsgplcax.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2joufzzti.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgnrrwtz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2uczzuiqn.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfehmxqk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ablsgfhb.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gt2nqreuwlw.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2ntsndjgq.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2lvddhrvm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2tqzusdjf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2mggigihg.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2fhdarxga.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2dcqrajmu.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwqaqfkm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2kpppqttz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2bfizcpmc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2inapayrx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2edybafus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gt2rqretmto.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gt2znxlgaes.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2sxhxkfjo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2acewpwcj.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gt2bcujokmk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2fxrykcqc.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2pfiduokt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gt2whwylzuz.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gt2wekzpapa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gt2nfdkjyan.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2taotatpt.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gt2vvldjona.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2uspxbdgd.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gt2vtlrwjor.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2okrprgfd.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gt2ulkuvwsp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gt2fxrbfsrr.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2insziogk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nilgmiyf.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gt2jnmfdfyf.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2gtqhrjje.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2qayxngnf.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2tqpgmgjm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2imtqgrfm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2vedgtnvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gt2pwkkzacy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2nmhywusq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gt2lamdplwm.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gt2vsflkpny.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fahjdbyu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gt2yethcesf.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2bicebaiv.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gt2idbvyfsz.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxqlktjb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2ppmfwhjf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eatgfyhz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gt2tolivxwe.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqplkbxi.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2qeraigrm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gt2mhsbersq.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2xtvoeyez.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2szdnchmv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2ctkftyyw.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vgioxvdo.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2opipteoe.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2revxlvkj.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2opryvxmv.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2qcasrbuq.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2yntkrkzz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gt2jncqislq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2eiqawbxx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gt2xpjuvleh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2crwcybsp.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2jgvguyas.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2efxfzqje.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2tbharshs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2xaqoqurw.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyecuqyd.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gt2hksxlsyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwhtmgbf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ricahitr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2xaqtibbp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2ibytskwr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2fdszorwu.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2juuvitbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gt2rbjpbcqd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2dmtxvjtq.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2efrszupa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvrmiqni.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2psuwfiio.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2zewmcswb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2titgwisj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2ejyawyex.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gt2ximanvvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2tkwndwmu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2ezdscsfd.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gt2slqxhoni.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gt2mrquqbim.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2rvqgrzwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2gwerjzmc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gt2atjrgnwu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptonoulo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gt2qfwwtghk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gt2pqvdnmxa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2idcfeayb.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2qdidiqav.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2ewcazjhs.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2ymmjtwpg.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2urumupnd.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2ettomcge.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2srcfnyir.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjsqcyfw.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzftjfhb.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2dfnfgiob.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dgpestqt.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2tmrocdrz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qhtohsbn.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2huzefiat.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2onghmrsn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2ovtzfvrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2qzrliuay.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2wedpzeal.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2tlglgsej.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2tqagfgyg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gt2plwsoqpe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyttmnnq.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2dgvrzaqg.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2szpdkhye.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gt2wzrkfrtr.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2llpvlgtt.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzheiige.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2soqnnznu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2nlxdiawt.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2jcbtjsiw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2bfxqzlnz.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2dpvuncga.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gt2bnmfqehy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2ofylkhfb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2yqsldttj.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2upbynjgm.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtedvvea.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2iaogyqyw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uotmwztw.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2thdidgzf.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2kkucqgwe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2wvvqimrg.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gt2qdbrttmv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gt2fmxwpvgl.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2dspwqcaq.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2dcumcifz.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gt2mtrytbfc.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gt2ncgrltfo.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2vcpowksq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gt2wxjykcxj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utmhtkki.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2jfmownah.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2kxikuclb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uszpbegb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2qwylajyv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gt2qdyjkxav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gt2zcvfaoon.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2yezzysja.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2hciikyiv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2bznwdcbz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ducjoobg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2dnyfldgz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2lrwmxdch.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2wslrksdu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2ljcupxaq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2zkfwlcju.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2hpudborq.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2xuqaaion.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2wjgehxfh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2fthxpvqy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2alqnynul.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2vftobots.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2berdzadj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2fvpvnorm.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gt2arozvbsa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gt2pvwvafrl.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2vasgjxlo.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gt2yuzeexdc.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2wqxjndvo.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2xkncrqmq.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2lddeeawh.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2nnbodemw.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2qcncgpop.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffaylhsr.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2qeiuzodz.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gt2ffsknggr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gt2fwsxlysi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2fftjdejn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2dfkbodld.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2yzezjlqd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gt2tyywpnto.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2uwwfjuuo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lznkxsmp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2tqupsozu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2pesyulbp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2hpyylhpy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gt2ydjppbfy.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2fjarmtun.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2tnvoijty.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2mrthrgmn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpaehpsy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2mvebuowy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2lfqdwqij.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2bbgayrqf.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2jnwmduxl.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2uqpeupjq.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2ujgfcxjd.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2amksyrxe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gt2jnaqylgx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmzgvpbg.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2qutixxqf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkirdywq.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gt2zxdnbbwf.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2lbhyiqiq.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gt2hionmcwx.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kouhbdzb.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2kbqzessc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2pugixcud.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gt2fnsqvzks.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2fawsxqhj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gt2jfwvdrok.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gt2widgyfdp.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2yzuphynp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gt2dvagddat.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2veligzrd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2arjfpinr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xnqprjvm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gt2xbncbytx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gt2pdxqufwu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvvpmuur.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2fqhtrrpm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bilngijr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgyjrius.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2eeqmejrr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2jvgjexjw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2tnrkselm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2sqswxzut.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gt2vngxkhiv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2mclqiwci.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2qubskwdv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmdsyeyq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2nccaxbqm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gt2yhegsibj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2unkzqfpq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gt2kybhujbn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2fnqozpxu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2sbuseuov.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2teqjuruz.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gt2mfeszlht.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2udqsrunp.html


<!-- 参考信息 -->