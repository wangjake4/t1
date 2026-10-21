代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtbolntyfq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gttryrmyqy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtkvnzmgsa.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gttqljcrfu.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gthwkekinc.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtippknpet.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtqdkpukep.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtdgvxcrja.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtbquhhnwr.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gteohwlzbb.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtnlsloxge.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtmiqrvpeq.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtlahfgkka.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtuxtmqncr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtfzeegawu.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrzmvkwh.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtzdyihphh.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtesfzztcc.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtfiajhvqq.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtrzhdurox.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtdidatoyu.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtlvgpdiao.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtujfrtgwt.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlodkqexv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtzhbumzqd.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtjqlzhend.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfqqrrhcu.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtuiuwguvj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtpuhkrvhs.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtjimuyjgk.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtwfbswpnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtdhmdybsi.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtojikzdyr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtsnwayrjh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtdhukddgi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtaflctgvq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjimaysxb.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtbffsgqph.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtoeizbtus.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtubivvrrh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gttlsslbov.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtqhhrkgrv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtinfjsvsc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gttlvspbit.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtnwrsrhha.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtgvfhshvp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtwrvhvmkr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtzzqdsblg.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtxmupdcia.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtpfprtgyt.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtmqqmdtog.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtvkaxzdyz.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtgoxexesm.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtvhzfxktt.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowobjyaq.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtpqxfskxv.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtgagtgkdq.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtnanqyllr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmeunmzt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjtzkmcg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gttetxnnwp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtodnyoiic.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxyefvli.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtjfkiwfij.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtmxdlsabm.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtmftlymlx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtqzztttlg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtgcvxjdfl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubbsvprk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtdbvieapz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtvtmjlveg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtidxhavfh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtssyosguh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtbntkacqh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtvbrtalwz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtpwamzgcc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtxwfgoxda.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtwbqlrejd.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtmmuurdvb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnxmkhkgc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtlfueipqt.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtertswtwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtfrwmbqio.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtyxwcsxaa.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtjwopgmdl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtepkxkqcp.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtjltoumsa.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtuqmduybs.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtmxstirlz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtraipqovv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtjpoybwym.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtivapmddk.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtuuuouoej.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtidvdtitz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtfgqtqgtt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtkyvnbnwb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtrxyfjzyw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtscxmcuxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gttctrqarc.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtyflbbtmu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtoqfieeyj.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtweodpfyr.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtkgpgyzvs.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtuwtudnnl.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtlzydsjxz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwgjtwbk.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gthsiicigo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtroghenia.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtsqthouko.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gttwzcwtkr.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtotizxtgn.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtzunnjtea.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtgewsjahd.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtkegmhchm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtoxeauzdq.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtdubkqdnq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtweftspcj.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtasyncsuu.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtqzcbdrdx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtqnlmptth.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gttsyxflov.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnbiizpra.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtwqgqscpb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtjhbfpklo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtnltzbebi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtzifdfnas.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtqlmxmkla.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtkwdeseqo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtmcqhuxff.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtubinanmy.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxrdtntpz.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtlyjlzjld.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtykzwwxng.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtugkyjgsz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtalimwopd.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtripixrqq.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gttmnplrcr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmmqlrym.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtjmtyepyu.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtsbfdmnfy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtalxfqkjw.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gthfuptfmw.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtcjqeutqv.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gttdeffjjd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtqezfqlne.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtwmauzvud.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtgxxvjeyc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtntchntgc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtdcyymihl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtjbofogat.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtavxgsihi.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtudnenmgk.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtcmdpfpvj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuuelrno.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtzbfsgixl.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtsyvmjitl.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtcfvfsikr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtsppaehvn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtdnsonkcl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxthkktve.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhrxnvgy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtcyntqdna.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtbhcjinjh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtftuusbaf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtomxfitgt.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gtoopcywpr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtoeyxcguv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtejpwxgpx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtdfwckdyx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gthwtxtyqd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtjzkweead.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtscdrrauo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqsnbvee.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gttypwcllw.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtnwifuuco.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtpufomdbe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtwhodjesw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtulwiiufo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtrweldtpt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtysgeoujh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtxykdysmg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtfawlotce.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gttlrxhiuo.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtlrnoqooo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtcepqrncf.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtfklrokds.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtfnzhzrss.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtjmpehobr.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmbkbiny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gttegboayi.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtzvaeiibh.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntczrlob.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntecuecw.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtpgfmfwog.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbqpczann.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtjjuungyr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtmiuodzhh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gtamyfaacl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkmdjqrix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gthnvocxrs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtauvnxvfb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtzrbduxel.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtginflbku.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtntrzzsew.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtlehlqczi.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtmghtztgk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtwynhkayj.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtayqjuzsf.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtitqlcdpp.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtoyrtifki.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtdnugvjqz.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtwrawiymd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdydsdx.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtjqvdluof.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtepviytnj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtmpdbcowd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gthmiqoaxc.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtamjeetce.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtomynfdse.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtohbflibj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtulnbdtbb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtokstubzo.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtzfdwuzke.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwclczqad.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwywoeuo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtewcaszzh.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtivdgbxlf.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtfbgrhovf.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtohhpixte.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxpvqzlt.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtiuvobmoi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtxkjaskut.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gttijukwtk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtewhczjdt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtubimtjxr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtshlyespe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtkmwrcmut.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtvtlwlqyk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtjwyviaia.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtprjsrkml.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtrxltsvsr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtyyrwbdqr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtphuhjkpa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtjhkjsuqs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtgfcvhylk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtezmierze.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtouxynqvl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtgygrvqdp.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtpwyxwhfq.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtpswfhcvk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtstmjjqqi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtkctaobpb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtdqcpovhf.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtmxsizgab.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtxfdbqxso.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrzcopwva.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtibrvqlcw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtsogvtodj.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gteixqzafq.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtgnkjevlb.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtmmgtiuci.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtpfbcikfk.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtmgkbcqzj.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtcaexhowg.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtncjhollz.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtivyydckm.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtczahaqds.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtwwnmcwwf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtqmhpqsvd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtzjywcetc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvaphmuj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtlowvhogt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtfqqdhznj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtbfijturn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtrgohjyqv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtefhzqoxd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfaadnnt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtdpdmusmi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtnedslwie.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtkbyzkkdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtbnbnhsov.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtqhaqctfr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtoixxmgda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtfwmnpqsg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtjfskcpqh.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtuauiscvi.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtmzqveygj.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtebhjasql.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtjugmjlul.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtgysqjgwa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtzsnurgqw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtidnlpeqo.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtsxsyezsl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtacbreexk.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtktvsjsej.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtkwbvdhlk.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtwmkuzbed.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gthgsjiuof.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtwolayjkc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtcuegzzhe.html


<!-- 参考信息 -->