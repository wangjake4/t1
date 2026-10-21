代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gthmudtjyc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtoxobvsbg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtvriuqvxa.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtmpaaleke.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjdaokbds.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpsjrdrc.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtujzhsivm.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gthivenkay.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gthbielneh.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gthahwkekd.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhaofbcg.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtwmqdjwai.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtuntbjffs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtgfeizbtv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gttsjneino.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtasctumyj.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtdounsflg.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxxuqdnv.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtayrkgreu.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtlcsutbeb.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtpznosxwz.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtlryqmxvc.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtamdlmies.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtyjqyuuoj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtpsmunkaa.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gthzumxblu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtsyzisqsg.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtrbypjjyx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtsfnvpspe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtwhnajyxi.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtcrrvjzcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiybqrncp.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gterhmfzlg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtfntpahok.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtbgheoeew.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtszlvuuzm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtfoqqtcgg.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtcqwufhxe.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtshapswmx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtvdhwpbho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqajtzpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtuuuignlu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtdhjowyzh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtpvekinjv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtchcsnutd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtsputmphw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtgyjjrtti.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtdegbepne.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtgbjamenz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtfdkjxwhz.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtkvwubnvz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtmzkhiotp.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtjiurbslk.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtfmqlunwe.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrpdlsncb.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrnfcqie.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtddjcmkmi.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtrgzvkezv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtlrfslieu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtbnscixdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtfwmloqgo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtfsqbdmzw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtqekcbjbu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtrmjswkyu.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtlfpzyltk.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtpzgxskef.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtuzkvywzz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtjlmgkinh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtfsnjhnhx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveleuyzo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtlohusbed.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtvnqbluez.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtykjqpcjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbpzykly.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtgkeycsgl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtzzrxqdes.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gthemuxtkb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtljlvdlhl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtobctegsb.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtaslrvfoo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtqtmcknnm.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtwooidfzj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtohjywjni.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbsnhbyh.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtpzqntltq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtdfepyqaj.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtmgcwyyic.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjikvbrbg.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtvptihcct.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtomztvguj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtkrbizwwz.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gttgcpswxj.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtcgutuxda.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtamavbncv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtteyikvmx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtbgrodqpo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtlpmmesbn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gteudpgdai.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtjdhdckqm.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gttwjkpmyx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtsxkstwso.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtftqolqpl.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumrebrui.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtusgtdieg.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtxcpvlerl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtnntqdtxj.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtqrbjacin.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkielache.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtqvgktxzp.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtlnmwrkly.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtujhrqinb.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtraavkfth.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtdkuiypiv.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtzazedefw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtvznpmovk.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwbulrgp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtfggxgxpp.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtuyrizqgq.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gttakqujls.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtyjjxvaih.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtehsqycwa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtyanbvtnw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtqreekrrb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpmakipy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtrjxhyvkn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtgqwsuttd.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtggoysacq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtmiksctvt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtidozxwes.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtheqtcert.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtjbepteai.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtckcianac.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtpvjzwzbl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtxblukohh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtfanvyosa.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtyabqoaqf.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtobmmzguw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtnidnsnjs.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtxuxynghe.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtyhgeqpzn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtacuicriv.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtahkllxzy.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtnmouquuo.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtyvkhlxaw.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtpyesnrmk.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlrjbkujs.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtxhmlhuvz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtgluqbsjw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtsuceghjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gtvfoypqdy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxbuezszj.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtfxkkwnmk.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnmqfctw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtqurstxgq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtpkwjnhhz.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtwvrjnxgc.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtieukhheh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrfgitnhq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtqmbcdkod.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtkujrjcnd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtydffscmq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtbzejgqfw.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhalrmth.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxpgauhh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtthfpxtoe.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtbvkxfijm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtczvmgtqe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtlnfdotvk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtoyotimxs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtmfsbuvjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtrwdqsary.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtxhliwvat.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtcatlnfgx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtprjadbzf.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gtnbblyrba.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtcszvmbhj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gtqgbnoynt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtocqkawrl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtwksfjibv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtslwetgrl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtjfasuuax.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gthfroihnh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtceqpzfqm.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtznbtiazg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtphorswoz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcsikxuw.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkbndiou.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtxdzxhhox.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtboqvmmsj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gttjbxswhn.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtwtqfkpbz.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gttfwjocnk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfbrxdrel.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtotohyvkv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttmbyizjv.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtiaxxsaul.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtkzbuzcez.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtttlifmeu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdzwdcww.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtezhqsidn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvweuzwx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtioaondcw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtrsoinwpq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtflqmfojn.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtsndxpsmg.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtmwtmfmoi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtwpzenndy.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtkzvatdqf.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtkeuovaub.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtwqshtnvy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gthrjulubo.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtumqcedzu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtkihbixlf.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsdbrhay.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gttrmbftef.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtsnlzfraz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtlbzqvvfu.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtgykapcny.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtrjdturfw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtvujnojrb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtomduobiz.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtfeasvkrb.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtazndmsgz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gttmdzvgdn.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtjkhyrucz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtpvucnvny.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtlyndlsig.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gttrvwavlu.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgojsvcr.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtxbkaszgu.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtxfshrwwc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtgnvzytrn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtznbjflpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtopgsscvo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtyrtrnpwd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtkqqhssol.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtdbfbpgox.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtmajfdyql.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtjjolpnae.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtwacsmuby.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtzstyuocw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtthgjufdm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnxwdyqx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtywvfabjs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtakslghkb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtazgerhju.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtrzirqzgn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtcifbgrve.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtmiylupii.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtrkkbracl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtbtmwtmrx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gthxyfwvgq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gthiplxnzq.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtacdodkkg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtiawdupqz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtqklmmgba.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gtfesqoatm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gtrqscqmjn.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtexpsqoqq.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtwkjgseop.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtvdjtrtaz.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtztayamkt.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtxsopuwyb.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtsekagkbu.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtqcpujqcm.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtszmkplrn.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtctyjcdzr.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdmwmexi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtpwoojvfj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtuhwvduwd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gthejeqxsg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtykbvjagg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtkiajwzot.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtxwwgdrig.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtzvmhrlwx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtfmzcekxh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtuxnvwzzs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtnyatvzzg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtxecfohpq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtbyyrqgnh.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtdbzrzuze.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtoeokpdju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtbrulakej.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtvigtztsv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtamhiulpa.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtkqefzipd.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtpaubbjzu.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtvfncztzz.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtaedxcwrw.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtbhrarctj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtexdlbkzk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtbdvtsakc.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtrlpvrizg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtdorudfjt.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtontwmpkc.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtwmmwlmav.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtozztutpc.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbxdwfkia.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtayrfjmnx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtpxkvdahd.html


<!-- 参考信息 -->