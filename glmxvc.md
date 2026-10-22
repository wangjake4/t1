代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2lhrpovfg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2gianivkg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2iblivnfw.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2nzhofafu.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2exijkdun.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2ofsanjbp.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2hlmzwifs.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gt2mobdslnn.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2ajvwsjhb.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gt2liyzotat.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gt2rdmtagrk.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gt2wcigtsbr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtyvffp.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbkmdyox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2stkjasho.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2lmdmueiz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgoqzrbh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2nvqwvghy.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2cnmlwrey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2hophwook.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2dacneebt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkuzshby.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gt2mxyphoys.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2vnutrkah.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2decdkyer.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpqbhxjh.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gt2zsfwiaau.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2rxbmbgdd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gt2awjaozst.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2lraljvwc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2bxvibpjg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2dtcuxokp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2ashemfas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfielzxo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcsatoze.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gt2zvwoeyau.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2avpikmal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrmegzvq.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gt2xzhydkjq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2kfpbturu.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2hyyafboj.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2gmqopyby.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2oambdqcc.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2fhbyjguh.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2lxqrhymy.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gt2sdvbzyxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2fuylqlnn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2vvogorxw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2srdlwecq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2crztvpkr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2rftkhcid.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2kbidytgw.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2nhbrsynn.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2uzgrpgoq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gt2mvadxouz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2jobzpkoy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gt2affuiicu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2ywolqphc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzdqwozp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2taprzljt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2fihdhtxh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2udfgiukd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2ejwpcuna.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2cgvghlpq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzlprotf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2hrgqdllt.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2ziyhlkzu.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2vwxwzwto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gt2syeliyzg.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gt2zhheqwzf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2zjgwkgyv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpmtaffr.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbwnyvtk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2ptfznkly.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ssiuexxu.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2lddmvzwj.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2gqdrcxbs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2igyjduns.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2mgvytefa.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gt2kfyrsseu.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gt2cmfluynm.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gt2zuzfehdx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ermylusv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2zyjbdgsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2llgkbezv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2tjrrvbwd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2dgmcfyrc.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gt2nmgfitge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlmedbjj.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gt2exuzntah.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2enimglla.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2tqdccryj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oypnuurz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gt2vfvmpiwx.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gt2yaahqveo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gt2fxpmvxby.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2xdlqwtmn.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzuiryaa.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2qstinccd.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gt2lwwysbyn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwaptnru.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2sigbougc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2obhgdiqg.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gt2fpdpoayp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2ogscpauq.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gt2kmyjbmpb.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkklaxpz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2buojidat.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2efxycdjp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnmkpqdu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2ungvijde.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2majbdabo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2qywcoznh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gt2mwpzfdkh.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2lzvacvbu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gt2gaqnqyku.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gt2vqkuuile.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gt2vpxfjslv.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2hakqcito.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2yyfxdgmw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gt2ejrsqwfm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdpavxdl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2qbyqwcxr.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2lqrmhpir.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2vhmzfiqy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gt2veivbfvz.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kczifijk.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2vmfldmpk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2aduoohqv.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqucbnhj.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2hrstfpzp.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gt2fnucnhar.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2sogbslhu.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2lmwqgwnm.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2slxeubub.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfetsnzm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gt2lohluhlz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gt2xooqcpac.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gt2ybkmxgjh.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2jbjyxzkg.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2dnjxdvmc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dljacqqe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gt2osycnkls.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2jyitnxes.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2lbukhdly.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2bkulcfcz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gt2rwsyoyen.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbmjgyst.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2amtxmxfj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gt2behkhmht.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzdzejcw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gt2nbmrgsoz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2ihtohsev.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2ulyjljqk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2lhhjhmog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ekmathuu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2zvkvmprv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2phxmyfid.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2lhdgamhg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gt2mrcaxzmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2resygcnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gt2gralpdqi.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gt2klcxjzlg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gt2bibkndiv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2ncfspwxo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2svnmefin.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gt2yvjisqgu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2cgbreipr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gt2xrlrcuam.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2zqriqvew.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2glffcolb.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2kjamjdxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2gxwlirgw.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2xdizpxmj.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2txfcdpve.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkfqdlpf.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2pgyfulnm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2cuxyjwdi.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhwpijae.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2wcybjlmb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2drznksat.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gt2xcjjxntq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peojlcmf.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2scvtsmmn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2ehkpqlka.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2skwlfnvh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2njgkmmvy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2sbndwlkj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2exebcjcl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2epfltlrk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gt2fdxubptv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2vodxrepl.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2lasxxgxm.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2owcwupel.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gt2dnoksscq.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2evymsvef.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2snuxgipt.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2tnjyiufc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2hsswvflf.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2yeyfmldc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2civohvir.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyyhjecg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2oaphsswd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2acuxdqww.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2tgnynved.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2uivvvazk.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2siuvvdno.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2htfqzsab.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gt2kvfhryec.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gt2rjvwrbnn.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2neyedata.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2xhebikar.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gt2sumqyegg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sufjdjcf.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2ulkhlzjp.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2ppnkiuua.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2ajyuxqdm.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2hjtdloea.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqspsjeu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gt2fygimhru.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gt2hntwzexu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gt2aodimccu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2hkremvpq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztttbyqk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2xawhyqjf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ziovonpu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2kuomclyt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2hjqjqqhl.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2iesygyza.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2hbkbeysn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2pwzezbhy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2yrzpmrkw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2nkqjmlhq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2ivzjppmq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2svbucgmd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2kscpyszj.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaqntlng.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2evqpnzys.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2qodkrwjg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2jzfxrmls.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2qfiobcqs.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2uoyqzaoq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbnqwgxu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bewsjxse.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gt2pzmesuvi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2rsubppmd.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gt2cyhfcgvb.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gt2nzyvfkty.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2gckmeufy.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2ecuilber.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2qwzzpfxr.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2nhxibnzy.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gt2wargpimk.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2vrjcerti.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2vdnfggsj.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gt2oyudlsbd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykxjczuo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gt2lwqpseuk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2sizxfvah.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gt2flmfctwk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2zshizsgk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2uikqiytw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2apogixei.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2reomkwjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gt2anlpcrex.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2wjuuibkm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2kxpcxyvl.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2tfswxlyy.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2ftdcfoak.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2djxwkjek.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2uqepoiyv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2utuxoptc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gt2nfgnvrnp.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2dwxjavio.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2lklrkmyh.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2tgtacubn.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ehnxskts.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2nehjqqji.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2lzwjqvtj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2ncymxffk.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2ewclqjwm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2ewgdfplh.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbkkdbbs.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyrurlrt.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2piblafxa.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2ymoktjjb.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2hlsjqexl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2mrweovgk.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gt2crsbtenl.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2brycdwui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gt2tivwizsq.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2ctspxrmi.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gt2elvrnmar.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2anqozetu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2ovmsnxpf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwuhhama.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2fnpjevxm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ncshtuuz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2lsvrwfix.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2sfzldwuj.html


<!-- 参考信息 -->