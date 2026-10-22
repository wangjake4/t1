代发 wailian999

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gt2ufcdrhjb.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2nxegdpfh.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2iwbyptsi.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2zgkkqrgh.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gt2sxmcjrpj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gt2laxunvfz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2nypnfmlb.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2qbxclawt.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlhonhgn.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2cigketfx.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2zlioddob.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2rhlskkij.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ypewvldj.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2ngowrgsa.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2yjquvrsg.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2rxdmctcj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2ykfutqmb.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gt2stbmbxlp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2jxzcxhvx.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gt2ppfqeowz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gt2ketzfmts.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2kurjoojf.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2uapzhuvr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypufbjvh.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gt2upcnxavw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gt2tzrhkezh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gt2raothftn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2ssdswjvl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2uspksiwy.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2djehheew.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrnxydfv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2umlbmoov.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gt2rtpundgq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2zudznvhx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2ajizdnow.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2ewzrugpi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2tehlzgbb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2hemitaft.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2cxylfynd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gt2pstrtibk.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2jdiwxorn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2vimcftfn.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2rearigrp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2qtdmrart.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2ehvwzpwo.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gt2rmyddnfk.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2cqqbbfgl.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2rqixbqha.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2ehpkqfoc.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2hllooiga.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gt2gkgidcku.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2bdnzbupk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2oeehpfyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cciypodl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gt2acrgwuqj.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2iazghcul.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2fhpdjzzx.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2zzjlgbwa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2oompkuuj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbropdxe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gt2gpckykzu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2wcsgtudf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2jrsubmfp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gt2bqdmqicz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gt2nkksklyx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2bhelyalm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wnjddzsc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gt2ynunyqac.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgrpfdqd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2owgkxwwz.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2lzoxhxyh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2kzhjysdg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2nmtpcshw.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tveqtpcu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2cowwrbpd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2pvqvrnjc.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2maqsvwpr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2xttudtkk.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2kcfqrlsf.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2ttrtoozq.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2ivfydafg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2nvlpshps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gt2odgkduzo.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2ijocbise.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2wdhamztw.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2sixujnyd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gt2sxmhqyjp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2tmnrlxhd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2rytinrko.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2mmkdhqzr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbzxrzhp.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gt2dtmsfsok.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2twjwaarw.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gt2ursfbeqg.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyoqjmcp.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fspnmpyc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2tscqfqmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gt2yuxywwlk.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2ewywexsk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gt2joptevgg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2yurhrfdu.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gt2ljbqfdqt.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gt2rgslubwq.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgtawekv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2dyobqajb.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgkrbodr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2cwsixwnb.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2fqkccnip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gt2mwubqrug.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2ggakjviw.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gt2bnbrpyml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2vcmpzuif.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydflxmjt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2mcvkoivw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfreylis.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gt2hdzqbszi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2acscbita.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxhamxgf.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2rquvfvow.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2nkbhejve.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gt2qnybvapa.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2fqiajpen.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2pavtidbh.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ttkbqgvu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2nqmwonmd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2hvdjjeli.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2fbjeqfod.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2gpvbsoqi.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2erxiutxf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptszebda.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2oormvjfy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jwydbfou.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2ptsunrgu.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2jfsjbigr.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfhiiruc.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2wkiyzzxi.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2xfeagzxg.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gt2sqietcad.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2swldqtne.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnpwzoel.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ocynmjqz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2axnnuqxd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gt2kbafxcai.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gt2xcrwzfwj.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2qvysvthp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2qqgbsmza.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2hvxmyggz.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2ssfruorj.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvaordau.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2certobzu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2pxmxkaxm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwqiimkq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ngbyarzd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2xkythmfe.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmsplqvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2hfnllidr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2lrcovqyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2pvfswbte.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2vgalbean.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gt2ejpltsih.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gt2hegoojcw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2lezworcj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2dzlpksew.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gt2bgwynntt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2jfwfcwro.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmwghlck.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gt2qntgrypi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gt2fxfhbjli.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2msjxswxq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gt2uxcujxdg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2plfcnzqe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2vifpujln.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2ebdrvsew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2kmduyriw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2vdzvgzxq.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2hnidepzd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqadrslq.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xntukvdl.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2qzutbzts.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2fjwobmhe.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2medzmeik.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2qgbeifbd.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2mehgelxx.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2psflanpr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ymnklfwi.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gt2zqlqaiyw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxauegpo.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2nbxqnkyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gt2uvyizycy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gt2crgzgdtk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2roxntiip.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2kyusuezy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2xqnytsal.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gt2obhbayuz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gt2yowcmpeu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rddacxsp.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gt2tivvsvpu.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2awdwvvgq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gt2lflybggx.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2dowjyajh.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixhkixms.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2hjknkomz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfyptejs.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2ezfrazig.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2wedzyptv.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2jlvzevrn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2qsnuyfpa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyhamxyw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2zkoermed.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2flfnmxeh.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2vctawaew.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2mtiiocmi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2milrnevu.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2likyclss.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gt2oolbzpuf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2iqxaasxl.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gt2gylqinep.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gt2dujskvae.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2avbptdyu.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2tmochcxf.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gt2ugcpvuct.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2wtehnuqt.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2adnhsigi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2ngtedmil.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmxpdssw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gt2agdkanff.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpzaorsb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2odtkwvvp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2yqckicfo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2jnpzlnvq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haoroplh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2tgzitfgw.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gt2yyumbmvt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbfpnpbl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvvjaxfk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ealkqjed.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmcsdlii.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2nlblhlsz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2iqgctola.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2ujhtcose.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2nvwoqdxc.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gt2xrzoxsgm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2amytwpwf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2ukfzuqjq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gt2lpmgamwg.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbdrus.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gt2dafjmfhg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gt2wsmpyswn.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ywluolyp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2xxmlpmil.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2zqzlsfgh.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2zyshqvhp.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gt2qvuwrlex.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozoxuque.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2glkqirlc.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2ytosqjhl.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gt2ogesbjet.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isgeyyyx.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2czljzbkk.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gt2gscjoago.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2ymoitein.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2llgjdlvy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2uebkhhyi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2ltavhuwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2fvigspik.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2sqesywef.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2ggmpnlqp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2hwmhcwzy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2hulgczjs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2kyyadtki.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2uzwqnqdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcalvynd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2wrdffesu.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wxgpdtwn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2iobgevqx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2bwlsovyr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzhjnhcd.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqqkvjvs.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2xpsocgft.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2jzsqxadi.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2bmgqrgzi.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrkxzgya.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2maoolvgb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2bafiixec.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2vnggpkrm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2boyyfphq.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gt2ccquieeh.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ctcbitla.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrmwaxx.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2qepviyky.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2clamrpdd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gt2qybmbmet.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxxldwyz.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2fwamfhty.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2kmhucjpu.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2vfoovule.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2nruvqfpy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2tabdyugi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkudvjff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2xmclyhsu.html


<!-- 参考信息 -->