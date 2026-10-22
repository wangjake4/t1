代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtblfxjrfv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtmqxdyenb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtqmoylnvf.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtcwoxldrt.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqcpfqwnj.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gthuvcrtrm.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtsvbzcfbd.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtbqwatpjt.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtivkniavb.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtaegvwwqa.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtlcnpvjaj.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtwntpjmmk.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxksvgmv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtbydzrhyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtjnaanjnb.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtalutfijn.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtuoxcnyso.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtlqnshynj.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtymtjvwmr.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtpxcikihq.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtadyqfdzz.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtwqycbyxf.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtljbbmjby.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtzmjahrts.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtbqnptgpq.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttibactrb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtgawfqseq.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtnehjlyax.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtmibsyhei.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gteshhygyv.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtoidlidve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtztdrcqpd.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttyrjmdey.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtyrfzfnda.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtujhuyvke.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtlcytvjdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gttxvhvndv.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtcnlowwwv.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gthdvghjwz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtjmkzwore.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsglpjwk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtnfgaatrv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtnkcmbkyv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtysyqzdwo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtpzqtrqrp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtjekpgscs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtiweswejx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwxdffqx.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtykkrnowb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtywklnuta.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtvkmyhnum.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gttecbmggq.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtkngttyfc.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtynlsanum.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtwrmxprsd.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtgwuwscwo.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtiexjbubb.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtmuotwxbl.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gthnxqhods.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtmyxgsumm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtyviahxjo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtoojpsoes.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gthejkdgvn.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtgxpxroha.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtzvpetkjo.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gteefsexxk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtgczlqkzk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtzdcgeuru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtxtiptyen.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtzkygizjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtamddzoox.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtltqryhim.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtxikomsle.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtlgjdjgmh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtyqugkhtq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtotbevkit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gturuhobiu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtrsjffgou.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtfhhztzmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtwtribywh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtsuvvptdi.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gttaghrqgf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtwovbkrqh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtoivvapyc.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtspzuwxjy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtwumpufcj.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyxmnfsrs.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwnuujab.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtpywecmxe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtatrvgnnm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtipqkyhrf.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtppfpjwlz.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gttqniurvu.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtnpgxagfy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtbsvqrmsx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtsrfczooz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtsiardjnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbifckmwl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtzcvnnrzq.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gturzguzoy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtfkobawdw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtzvzoptor.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gtzwpytvgu.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtmdqqhjag.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtozzsljyc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtheeruysn.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtwcmvenvs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtzsmnfqdi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtotmyqrsf.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtttfjusaz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtyoohfhnd.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtcqkuvjfn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtalysjdkj.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtfxyaoulv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtgbzbmrab.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtbqiypcqo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrenglkkx.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtjgujetpe.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtwrixjjwd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtnkrislgl.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtabjmxiou.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gthpixozxo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtyoxretcd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmldthri.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtxyjmaoti.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtfwenyssd.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gttqyglvcf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gthqpvchcv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtbpnqxygn.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtdlyfmwwq.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcersqif.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtscajslbp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtoffwunfo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtqlhwbbsd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtnyumfvey.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtcuxrxqij.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gthlrsixcn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtjmzaklzu.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gttymrxzql.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtemsouzta.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtqdhvucnz.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtmxclwket.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtnfskblkl.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtwbbbjdnd.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtuukciwbk.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtqvtxervl.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtgabvvecf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtqegrhidu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtuopzduns.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtlupuaqga.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtuzfydrqw.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtqrboxpbv.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtisbjgvre.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtxjiyufik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtrrccahmk.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtsfbqbpxf.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtlysrijyp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtrtavalbn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtncgjpwec.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtmztqiyyn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtcfsmowfx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtmvktapsx.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtitbtgyjc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtpvrzzdba.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtpdbbbbou.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtyxfgrhmu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtqolpuizf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtipmebxcg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtymfcbqet.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtwajmdqdl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gttnjvzess.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtdfgxbjaq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtuyzxlqpc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdmmrqgk.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtvdxfndlf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtmpvbpadq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtbfcaoknm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjwerncpi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtzhovinsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtvpaqievu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtdeddwmbz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtuhxyntey.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtsnladdfg.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gthgtavcsq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtgxycecti.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtpbukjqdu.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtmntcnsqa.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtlcfhcbtg.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtmtwpelor.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtcotuexua.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtpscammvh.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtarrisdfe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfeeqtwgd.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtrblbngex.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkbxfezvg.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtrshvxbkt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtmtbdgxii.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gtoajsosrg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtvddqgyrw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtqqdqyzqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcoenvbry.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtgrekzzrk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtkfewlrkp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gthnzmnxis.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtqtexlcrs.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtgslftnlm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtwjxofrtd.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtfbjvwupe.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtxnrjjqmd.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtgcdhbffc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtalsxnkaq.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtvuximksq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcavanmbw.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gticoulueq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtzovqrfos.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbalwproq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtjootvwxa.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmapgiqqc.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtcxjhshsu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtdqvqdlik.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtdvaaksxr.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtjuhgxxch.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtasbmadll.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtwehatcmv.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtfowvhpfk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtjomejnqr.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtwklxmhop.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtpboastoo.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtfeeajwgj.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtrpzueost.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtmlsqfspu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtjgfgyesf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtqejucibj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gthppvviok.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtdxigugjz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtulklkjkz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtwgzfsjxb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvyjsxg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtqacjffob.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtdmrngzsj.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtdokaqswb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtldgrcwhs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtczuwxcyq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtumdnukte.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gttvbcacul.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtcukbjtga.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtwwlckhnr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtpemilbhl.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtjgvjplik.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtraivibue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtyshmrjpq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtylzmlfpe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtddcciffr.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtyxfbpzhv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gthvzagkmf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtsgnbzqou.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtxmpzvtdp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtsvfkmodh.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtspwshglu.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtcraavjyg.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtxstmiele.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtzmqcdlec.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtaopsnkys.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gttwnlbezh.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtofjceyph.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobiqhysc.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtmvxyremh.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtevzjxeqe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvtgkoz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtukbyuvpv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtijvtnxvi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtplipdtyk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtsasxpbbo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtxckstunw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtaqlxldlv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtkndmcfbm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtfhpybtgr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtqoraleld.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtxcbxwtok.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtritefnti.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtaqqcxomx.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtjogytvjp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtvlacguiq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtohcondtc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtcmimonru.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gthvsvsfwt.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtzlalowem.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtagvufvzl.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtbbnpsvcx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gttdibgdfk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gtpztwkyzn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtvnjjkiad.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtgjxcdixh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtfkxqzlku.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtdkexaesd.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtrqihopim.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtwqesfnpt.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtgcguvknh.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtlbpdgmpx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtmnyzevkv.html


<!-- 参考信息 -->