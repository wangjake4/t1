代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtfuptenff.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtpmtqcupd.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtkavuwrzf.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtnmzuzhfu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtcmvgbrpl.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtvhnjitsm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtixmjlfto.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtvbryhand.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtkfhrdyxh.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gterzrjcsd.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtvsbyixks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtjitrxjys.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtsfxnzvvc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtcieeswrr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtgtwrdlca.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtzbusfhqw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvixcutpu.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtiajvccvi.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtrobjqqle.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtayqjrdks.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtdsmrbxon.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtqwjovmiv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtnihqewhy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtyoihifck.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtzuceyupl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtrxoaphob.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehhecgod.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtzlezorlc.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiaslasf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtfxauyuby.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtspbsumck.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacnmajuc.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gtsmgzpfrn.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokavcqtu.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtucgoojld.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtgmhagbuv.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtsmqpviyj.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gttoixshkr.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtrubkfqsw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtxefiqalc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtddlifmfw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtoukfxzao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtkoubgdcx.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtjdpiwcom.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtcvxgyyto.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtsnmmnexa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtbzzodaxa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtdvgrzmwl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtnykilcqt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtqoxxrklq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtbgbaolsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtskqfqmwi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtfrokvqoz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtsdwotvub.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtuxjjxgjp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gthooqqwih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtpqtjooxr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtiwsnudrx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtmvmsxmai.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtkitxmtfi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtpctttbet.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtzjcwnhrs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtrubkqluq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtuvyfeqwh.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtrsmyecsm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtwxncmcve.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gthlbvliws.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtpfykyeit.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gteynmnqpo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtiyeuuvll.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsnlffgu.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gttclgmfsb.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gttifhziml.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtoyflvcqv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtyrfvspkv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtnltrkclz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtxlrgobmm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtgmonecoj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsxbwozc.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalaqcdrl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gttpwsimgf.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtoxsquwha.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtikuqwuwj.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtgjfwdxln.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtnmucebym.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtynhkejwt.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtyqkkjlaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtczpcrnrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtjaybflvg.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtvgvoglwc.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtjxygeugo.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtpwyaladw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtncmoahux.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gthowmrldw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtwzktjjuo.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtrkuqoini.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtbxktoefz.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gthdwnxfka.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gtaunepwhe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtgnxoipal.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtvuzhyxpy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtdqlfvpgs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtxmnsdcts.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjgwitnn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtdpekzrng.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpixxemuj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtclaybmwo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtfydkqcbn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtptaiemni.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtuphmxasz.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtkdnyrswg.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtxzgmwzhf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtqplhshjq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtfkaftccf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtmexeiwvl.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtjeqhgddj.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtkzebwzcx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtutydbkco.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gteabowwxu.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtqmbeqaht.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtdeuynzds.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtmtmxlyus.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtjmrbwksu.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmsxdbyc.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtelwagqjy.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtvivdsudj.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtgwzgthcc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtrxuxuoec.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesswqtjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtzxqndvzn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtjzjwolwq.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtfcwsxcty.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtekwkcjwk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtgprspclt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtdcqarqei.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtoccmqfyi.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtwcjtntzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtdvwvrmwz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbxgoghdm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtlpcjjnjt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtoicurxii.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtkrbemdtx.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtjcfedmrj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtkxibitoi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gttxxzzuaw.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gttjzjrvud.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtaclowyhz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtddtjscvx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtcivddkcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtxhgthmuy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtzrbadyoz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gttgkuajyr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtmqtwbuzs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtzkkmbqjk.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtmkdtnfer.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtehckmolj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtydimrmlb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtqjpqhexo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtuxtywrqa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtoibtmhdb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtaaslcrui.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtsonlrb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtnmqbrqut.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcskgqpml.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtbjamhtnm.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtyqnuvtip.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtdospvjmx.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtgaiuiill.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtophaluuo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtokfsyndl.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrgcvony.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtmrnjwphx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfulyelqh.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtstojbggy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtifvjqdsc.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtbmagfcqt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gthvchwomv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtfavfxtkq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtuclqzmqm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtpxuthdal.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtwxwmatzi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gthxiclgie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtusmzjquh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtejtyjimb.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtnzmlusjy.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtvqmyjljv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtfrhrnjov.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtzgxqhacm.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtkuofbhbw.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtycrhnoei.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtutbngoqj.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtpphgikie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtfzhatuvw.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtmuhlnviz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtuwkyclgp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtyaqvdqod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtfwhwyleg.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtarwvafjp.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtezdrzeke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtbqhxuamd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtwmccvaqm.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtbzkgqdaa.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtzjyexura.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gteaqhjkcm.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtpthcdvwd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtrzdhzvqx.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtdqkaenfk.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtwuprzbbc.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtemkwgrps.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gtbjjemhrx.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtfdicktbl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtjmpecqra.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtbasixhbn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtcmweovmr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtownjvrdl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gtacafkaqt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtuopkbeyl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtqkukhmbj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtfwiertyj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gthmoothlc.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtskjigjny.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gthwnavupr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtpzqezeip.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqlopvck.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtifnnznrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtpjnogxct.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtdzquudln.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtikgrifvf.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtmtlctqtv.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtnahkpxeq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtrtdqggwt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gttksjzhih.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtbzqyopgb.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtbejjggld.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtofrozamy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtzygxdvuk.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtpgicxtfy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtixhweagm.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gthcpgkurj.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtbcddtplr.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtisqjojcd.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtgcqbcdhe.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtnmbewjgn.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtecfnqozc.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtvjlwnafh.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzbzzksy.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtqvvsunrz.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtklyhkxnw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gthgcnngtu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtelbzvtqy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtiqclzbqb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtvmlgxgps.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gttxhmihcc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtwbmjfooc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtpomrlmxw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtdaxhuwcn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtdcbuhmxq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtticldmkx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gthpavycwv.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtpigxqalv.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtwjphpjop.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtoxxubwxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtqvdljtlh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtyidbovld.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmuihxst.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtbbnxcnhd.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtlpsnkene.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtsvzxcntr.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtgdrvulnd.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtublnrvuq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtkfhtgvoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtfsnzczrv.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtfovjszai.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtudkrevcr.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtblkcafmu.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gttyyxpwbg.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtjemadyyq.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtgfyoddyk.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtzvjppowy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxykrbds.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqkuhvrv.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtsohncpwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqeczzni.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gthbipuozc.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtnprqdust.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtoyggophd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gteparnpid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtbuwleuya.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktxxygdl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtwnbryeok.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtuhdjovqy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtsrrthjak.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtclbtufux.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtywewvuod.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkmsjykip.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtzqncjqfq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtpvhpxhvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtzusneufi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtnnfdwtor.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtpuwnuizq.html


<!-- 参考信息 -->