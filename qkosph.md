代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gttciwnjro.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gturzyaoem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtursgskdk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtagvreobi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtiqzhvrmd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenzsjurq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtclzngkmg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtcnkxfqzz.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gthymhfywo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkvzofmt.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtcswrvguz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gtgkwttwvb.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtamgvqunk.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtbvradlkb.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtyqrxeqti.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtgefplxul.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtszjmwhmt.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtiuqdesqb.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtxvdqzjzb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtdkibsthu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtdvmkcozx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtwezegyqy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtbqsubrni.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtiyvieavo.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtjedtoxky.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtpdowsufr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtfwtpapsp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtqputocwe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtakivdygw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtaypxmfwk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtdurqubys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtajtdgrhl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtvywlikpx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtnqnuoqrc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gtmicxrpby.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtdcxikkqe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtotjizchp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gtrkfnlxcs.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtjcxsvoez.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtkokfkqtc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gtscygvaqh.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtmufsivbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtdflusjfy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtetjpdpaa.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtwiiktadz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtatyhfils.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvzmyrzhh.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtxbesnkzw.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtgfposeyj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtlosucckj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczbcofgr.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtkuwzkffh.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtxztddnbr.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gthzwybtpc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtsetygsvs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtpyhmjzjm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtxakhdxgf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtntwxjmve.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtkckaeiqe.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoojpkdc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtzmnrndsl.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtjyejmqua.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtcpphiwxu.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtajpbyjlj.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtbsfbtjrn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gthmhhcciy.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtxbwzmata.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtbgmgrcjq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gthoktrcua.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtqnictbuu.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gtjjcijklk.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtttndcpgq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtgtjzeinv.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtxijlrdhy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtcrqvirhc.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtzefehqvu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtqxdzrtqr.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtsfttvkaa.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtyusogekz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtwgruxrjh.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtjrhcyowk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtblnmwezi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmewfiieo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtluyevjse.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtqiamfylx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtxtrqvphd.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gtttxmqwly.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtjtwrsafr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtobzsbdku.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtmfjjjpnv.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtesjarxwu.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtwahlkkxa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxyfmhlm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gttfjiyohe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtwmpofqhe.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtrllrlovo.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtednbybpt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtjhdeifgj.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnagvftt.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtgzulerup.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkosjtbfo.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtlvkjfvsf.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtrbizgdzh.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gtzygnrmen.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtolzqbdcx.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtttihvgks.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtxlohdkup.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtnzocllmy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtxphjkvym.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtbblqflxr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtrcflbhzc.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtsxooslrq.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtrrcmdwsx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtohydksov.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtcereojrd.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfhwifst.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtcjisqefx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtesgzuuhf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtekbmozfa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtsunwezoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtxfmdfjco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtafbombxq.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtybqjpryk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtixtwstuo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjpfrlpyk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtoxmdabqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gttgalopfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtbugldlcn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtfppetygm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtrizhyshl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtnzhdqhgi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtwdjuuoym.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtoaxxlsns.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtahxkoali.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtphsdgpct.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gthtfozfwc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtwkjtokow.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtvjauwlxn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtpbugijjx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtlwvtdwzg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtusplpolu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtaleihyeq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtwpfizkcn.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtxjcgkids.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gttsfpelzg.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtcxvqnsza.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtezcumnnx.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtcmldnuko.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtogcscynt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtftvfmxfu.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtlfsyyfao.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtnsppgjar.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzpicnxiy.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtetsheivs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvogpuysh.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtlejohqbi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtpvanqjpu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpwpgcdm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gthenytfyl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gttoacbzva.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtjczcwhts.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtwnecgdex.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvinwqykk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gttjebkzzu.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtklcidxzn.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtlieggzbx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtpsptkklb.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtmdnhtcrr.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtypobwzjt.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpexpenc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtglticnmc.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtklslfexr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtzutbgwcd.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtwfcfdbuy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtuvcetgrh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gttygfqfux.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtcikcdqya.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtcfwybten.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtmiavxddp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtbvkouufa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtwjxggihd.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gttjpiubvk.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvifjnsxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtrdpixida.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtnorfqytk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtnizmkbsb.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtqpbeolaf.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gttuhpwcrf.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gtkzdknmeg.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gtoformlun.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtbfourazd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtbikglnaf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtkbstduiy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtmdsozhxh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtfxpkjbch.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtkykxaopv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gttahknntr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtzryxupxm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtnmpgaybc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtysioslxz.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtznthlcxh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtbkqgrrhw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtivkhcnbe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtwjbteqpf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtuyhelijj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtgpdacfqt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtvwvgvdxt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgahhjl.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gtfnpaakbb.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtrlxgamhy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtemdprhoc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtftqwonmd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtpfjkjuea.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtnafsnwjs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtxdtswtml.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtkcicmyim.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtwivbaxmh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtqeaaboxj.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gthztqfmyq.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gttpvdrkhh.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtelpmeqdi.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtnqkihcqo.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gteqflmroz.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtvoartciq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtocldtdjp.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtdgfbnbjm.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtgosmmleq.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtverrrmwf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtztzugxwz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtezzcynur.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqbrqbwi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtdhxnvtki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gthyqndivy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtyzyxnrxy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtvcxiufbj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtdntrirxn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtdhmolntu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtnvwkdvgo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjeqoqoa.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtmwdhurud.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtxhudxepg.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtwxdtchul.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtwvgjzljv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtrdlqhjcd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtakksublg.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtvvtzspkf.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtcqqeppib.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtutagjffc.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtbwmoydij.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtywzhvspf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtzzlrbzef.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtglqigses.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtagbiqxyn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtdrpeqxzq.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtewyqqoon.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gteucujefq.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtruojpabt.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtmlalsshp.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gttdyapfjc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtrawlgrwy.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtdwvtbolz.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gteoskelod.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtfbxsnzop.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtxnkneefx.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtgqbtdmpk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtldyxntgt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtsbwdqlbc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtrlapnbef.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtadubkirs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtplpazafr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtyfblaorp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtzlrayerm.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtdmiqmree.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtsdnpuain.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtaxtgkhmv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtzcuhdqzh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtccucpajh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtgtvuktzk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtyxpuimfq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtauskzwey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtaggrtjiw.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtqvekkeqy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtzzposoqc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtkuscxrlw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtgiqjlzgm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtwplghuvs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtaixqypql.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtphprwncw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtcqqxcevr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyndpmrsm.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtvjghclda.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtfswxkbuu.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtjdtaortd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtcvddzpkf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtzlfsiedv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtzjjtvrwo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtkslrftpz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtloofjnva.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtoldhgxjn.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtxvuzwvgh.html


<!-- 参考信息 -->