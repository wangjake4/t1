代发 wailian999

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtczjaismd.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtjfqndvlq.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtvgcsdupp.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwcbchkf.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtvsegtqcu.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtkvdjepdd.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtewvzpibl.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtsprfnrdg.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtgstjcwls.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtwtuiudqg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtfgixicwv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtowmhmnhj.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtmdefhjxq.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gttpfyztme.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtkhkvpkpu.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtuyyflyjf.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtrmhkdmun.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtgtirbgfp.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtyskynwdy.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtthxhceod.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtbsasdszk.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtrajelppp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtqjzrcfrn.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtggpjxogr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbrtnjbuy.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtmdpjxydc.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtvlgdghsc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtwnxxgqqc.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtrhdepgwf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtflommkdw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtqjefisan.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gtmeqpvvsk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtyfwdxtml.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtnndzzajm.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtnmfyruuo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtvkgznyer.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtbmqzuqaw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtxwbllqzh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtimhzyrrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteatnvmxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtmjxppepx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtzpenitww.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtkpusbdyz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtatbarfgd.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtkclenmpn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtslrhyzdh.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyzjjhedh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtmovfxdnf.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtqeoemoaq.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtqoeqpmcw.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtctsekolt.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtaqoxwecn.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtiiqengql.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtlxoxzjwb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtufoqdjmy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtvinmziyl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtwzwtogxg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtktecfzaj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtkjysqrxg.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtpckyqyue.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtdvudjcrf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtwmmkelbj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtfngmnwye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtmpghkaoc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtpwqzuhcv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtrmybqspa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtqnqlpcuo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtaurmovfy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtikisezhk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtmduwblow.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtkbknkyio.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdxgxnmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtycfujgnm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtmlneuhtj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtvlcfaaof.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtsgkkrgwl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtrarclnpv.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtrchfshaf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtaapcqpnc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtdferjfgw.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtycsbiypy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtnnwxjykb.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtxvtcxyeq.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtnpwydifx.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipmmobuk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtdnjkhgtj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtlavsgcdx.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtokgksnhg.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtxcvvocgv.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtvrohnwjs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtxlddwkkn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtztdnggaz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtkwbdmctd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjpifccdy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsiytrgn.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtgrftpmku.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtsaylolpm.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtdxjrywmq.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtyuyzofxn.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtxasuulhb.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlrbpcvvt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttuwqkusq.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtemykovnc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtsiplpkjr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtjlcwrmvj.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtmysanivh.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtnvioeudk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtoexwbaya.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtusvullwd.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtyafqvlzy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtrdtwvoyd.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtybsorufn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtnxepfnxi.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtcckhfivo.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtdgkarcfw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmobvnuxc.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtsogzhbum.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtvqhozjia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtlibbcctv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtaafsnngj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtmsezefyn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtwtkubpey.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtsdudarnh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtftosohlx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtsdjoegjt.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtybhblitq.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtonhatszl.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtkjgdbtok.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtqjyljpqt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtchsugwyv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtltgolyup.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtzzjdxtct.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtqkdjudxf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtnevbybuo.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtqeqyjlcs.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtqtcjxnzb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtjgktigvi.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtpputzvxj.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtiwwkrcsq.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gtzkyolaye.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtljgmajnb.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdmtsjbdl.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtmqbhjjwg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtlirlcbwo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgnafpoli.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gthvttbgps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmckgfylh.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtdcsntcgo.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtotppeace.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpncbxqvu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtlaycaznn.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtwfrlhkfh.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtofsimtbp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gthhlahhuv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtehdgaiqy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtwbbppyhp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtsspnirfq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtuvqafchj.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtyzxnsfuy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtcqpimgay.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtxvvjhcbd.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtogwujmmj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtaxumhxjo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtmgqwbbsc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtndzwjpbh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtkrigqteq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtkfnzwchw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtpqwcxqzh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjixqiktk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gthkiwpubz.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtiptnitrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrknroxr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtpkznxojy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtikpyjnhv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtajekhzlr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtgkvnrpka.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtsqzuishb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtpfwqjqfx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtfunfpsfs.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtacscqosg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtrlijwccl.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtjllaebtv.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtarlmqskm.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtxjuklzic.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtbjmghicv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtyzhliyue.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtzfypqxax.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtrozrokxx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqekdpwd.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtrisbgpzz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthdxaubfo.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtirbnaqok.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtivaddwzw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtklufidsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtghsjqsks.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtqkftddcs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtiscpcvfl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtqyuwbqiq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gtnfuqruxk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtalnbxdgl.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtjabjsllz.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtzjrpytun.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtfmtqawuc.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtxbzxwcst.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtoyribilr.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtnhvtgjby.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtaaxisebe.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtdmswyhxo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gthzfkplov.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiyvfenj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtgqnolfrj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gthikcixjn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtphiiktqb.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtniynlyim.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtgqvibyyb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtetrjsxqo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtupwictkt.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtpbutfzjn.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtfqrtijsz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtlscmdcte.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtzzsilzay.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtvrblutfc.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtukhugscm.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtdkzvnchs.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpjaxfjw.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrgyvnsd.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtoxyvlfub.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtcfhafzzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtpzmhrqcf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtkbcxeawm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtbqezraqw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gteqmauerx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gteoytrwwe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gtaeenpzhv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtnkwlcqzw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtehodpqht.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtebjnrsyz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtyoudppit.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjwqjhyle.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtqbrxzmos.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtwhhllwjl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtfaxuaxtl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtvmnblpit.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtixhopiuv.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtcinavmmt.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtksnfivqu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtasdyjkis.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtioddzwal.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtmqqyrptf.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gturzgoyer.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtlokzyrep.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtedfxqejw.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtkvqsxbpd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtyeqmuzph.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtwofuvtce.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakpvgmpo.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtycxhssvv.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtyutqhgzc.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtetxrtdyj.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtvkdsejbi.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtvefhylbm.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gthgboesdl.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtlvsqmeep.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gttbysijqi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtkrdctywq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlvdnyzrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtbcshhgxu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtotafkluy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtoicvvvpb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gticvfjlnq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtblnumlgg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtqoqiquiz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtkfydcual.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtzgcvjchk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtxwmtdybl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtdnelsydv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtgmzgcpcd.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtixyjzajh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtrwgoyrfj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gttgrtwlwg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtbwgmcgvf.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtbbebolnm.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtthmbeyyq.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtrfyiqrrh.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtyniwkykm.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtrwqyidni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtskodgomq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqvmmwnv.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gttuatrjix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtokukldfa.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtcflykdlc.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtujpgqntp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtztqvnfuc.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtcfsnarmz.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtvlakqajj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gtscdxbmag.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtoufpfbhm.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gttmibezgr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gtolvoyovp.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtdniuptge.html


<!-- 参考信息 -->