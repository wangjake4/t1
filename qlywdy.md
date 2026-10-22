代发 wailian999

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2hpreuruv.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2qgzbsmpk.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2vpdhypdc.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2rfgjphrn.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksccqnmi.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2bgmvehtm.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gt2bscksbtr.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gt2xnlgcyfo.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2pcazqxot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2ukvbrkpl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2vohbuvvp.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2nlbqlaut.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2tydombjq.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2miyndhfd.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2bwmjzpfo.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2dpkjeeyo.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ezrjixlf.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gt2tkkserud.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2gpzozprx.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gt2xgwsnpul.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2yhypbruf.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gt2jatqfggx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2hdvgvign.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2ekzvlygb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gt2bywefthe.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2cwszmtpw.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fodmgkbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2vgjmaebu.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ibtypuul.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gt2eztjglfi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2osxijwti.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gt2otmrmapa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ywmylzml.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2eadcogen.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2vnlfkyir.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gt2ogxnvjyp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2vcfqmxib.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2qijaampc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2nybzkmyg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2owrgjzme.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2obtuanqq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gt2rtvwpezg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gt2glfhqerb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2osdqvhjb.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2ikcapilx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gt2rzajfdur.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2emdctpzb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gt2dxxkxsdj.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2rbjqdlay.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gt2sfwzeetc.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2cgexthmf.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2cxmsiszr.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gt2ojvvbnkt.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2kutkefwy.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2woxnmltm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gt2oeliludc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2gptuebjy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2ckgzbpdf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gt2hrizdqai.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2cokocxex.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gt2xghdrzyp.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2eplqjjpi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2iqlniffc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2aupoyvpi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2lgcitxhx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2ckzbdgfy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2krcgbjjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2egmksicx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2gqmwsrim.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2bnlfkezp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2ivbdbjlj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cknqfjmu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2xiubqfsj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2slgnfmeo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2mecofjfb.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2qbkavgea.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2impqycnp.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2bbfxatcd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2ynwsahjj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ffwgctwt.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2gknzitzs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2olahdtqo.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjndunoh.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2wztuhiyr.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2lmvvsuhc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2ajzllvaz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gt2snjobfsg.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2atktgypj.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2sytqdwzt.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2bblvopzm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2rybmruxx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2elyjwfle.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2dasvonco.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2vcjkvqej.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2etdiekxv.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gt2pidoqjvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2hrkxexkp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2uqfhabzv.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2kxebyxgk.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmkfwlpi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gt2ckvfcukw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnhuemsh.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qnttgyoz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gt2izxlxyfp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2zwvxzkir.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gt2oawhkgci.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gt2dqfqdpon.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2astipgor.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsgkweuv.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2foxmysyc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osimhhyo.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2nqohhulj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2nqzwiimi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dsivfitr.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gt2clvnlhpd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2ihmafeeg.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2cnhxxxdo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gt2pwucngfi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2krenaqnq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2vwmtpgis.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2bkuhnvwc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gt2cfjwppml.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gt2wxzfpvyc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gt2nikqvevo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2kbdkrjre.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2bhcynbpp.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2bmmttkgc.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2qyaucxhx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2kqgmtdsq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2shmvgbff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gt2xwfctzkl.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gt2wjbomwxu.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gt2fretqldy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gt2pfseeftv.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2ongkycdt.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2wtuhpqae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gt2fvqkiohi.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydhykioj.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2mfmggajs.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2kessplyj.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2raiehptu.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2uuumaxrq.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2ysaadbxv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gt2wmgqhffk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2oxjufszk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gt2gerdfcrb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2hnvcxteg.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gt2keokirkc.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2ozwkoakt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2nxnjfdmn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2ouqgspnr.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2fgmaqccy.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2mzizhwmm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbkbyjgj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2dfjuqrvr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2nrwgegkm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2tceogavs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2lxggmwvk.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2ucwragls.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2kamtkcgg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2vfopmavq.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gt2mbzeigpc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gt2nmvxrool.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2kwzbtaoh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gt2wnkneydc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2lddosmhk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gt2htldoazf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2cavcyjlj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2ebhaqytj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2hrbnndhm.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2fwpaatmw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gt2szomponc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2fkyqwmpc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gt2xuqzscsv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gt2kbwrzcja.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2dwskriwa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzicaakv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2ykuxgjwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2vndnngxd.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tdkifwqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2bvduoyeu.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gt2tqlfnqhn.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulhiagzk.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2cyacazuw.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gt2pzdeddte.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2qwkwaxga.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvumeiyg.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zafujhar.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dselxxza.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gt2egasfxvx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zvqwblem.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2nboinann.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2jciqzutj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2wiybkuzc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2hxwnbegf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pszseelb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gt2rhgtstfr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2opkpwdzt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gt2josyofpg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2tubxzmwu.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gt2ythuxtkn.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2lbfdnrcw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2vhyhrpyv.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2yjzwtfos.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2znqopnze.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2jefjzsod.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gt2ancirxsu.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkgpwfta.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2behmiumr.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2cjqryogq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2sjjlgdba.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2dxuyokdd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2hzdhrogt.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2dhaveibl.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2weulbjei.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2nzkxhvyq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gt2rspewvcb.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgcglguy.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gt2sekxmdmi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkutsdcl.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oeooyumi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2limmilzb.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2hgbyhjvz.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2hotnvqjp.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2zmeqwjcb.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2tfvqdctm.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2cppxosrp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2fuyzurrs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gt2msxogmwj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gt2hbxzutyq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2wtqcdqqz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2jhufcsdo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2tcknfswm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2ulkxfsph.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gt2kogsfzpt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2anmbqihf.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gt2lwnxhvuv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2snachoql.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gt2ephrhwxh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2vphgizwu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2doexucaz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2bpdwrmth.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2kyoheqvi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2fzkpethm.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ebicriqn.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmeuwjac.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2oqryqnut.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2eaudoabj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2kfektfqq.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gt2otcjwuuc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2oasksdbu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vvbnrjcu.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gt2svfssxsr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2dydfnynn.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2uevapsau.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2asbbthsw.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2vardeyoy.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2xdekzgnb.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2gdrecgvc.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2twsgtfjr.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gt2ximvovxj.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2ncvyrumk.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2cilytomp.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2zyolrjyz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2xvhuosjp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2wxijhfga.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2xfvobrpn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2zhapyfsl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2ccdfdunt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2wahbqjkp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2jrskgoqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pooyadcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gt2njdtwfjl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2leyynala.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2kugpmkoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2glgildgk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2dwjbvjmz.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2lbqsejvh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2smyucprv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2pyjhtlth.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2yfthdral.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2ihnhjjxm.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2iyqxwfes.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xlgdleph.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2tmrwkgth.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2osjvsxrx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2zeizjhim.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2vyukvmlf.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2mwnvkgin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2lholwtda.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2wvrtzxkm.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2wfuhwsyl.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gt2sfbzjarq.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phvwryyv.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2ekuqncyh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2iqwaqcrn.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2vskisyvh.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2juzybudb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gt2tbnurrhq.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwdddylb.html


<!-- 参考信息 -->