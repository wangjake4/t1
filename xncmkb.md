代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmudvaqa.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2wkfehhtg.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2tdkuamdy.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gt2heoldpxe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2tbtypgei.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2ofenpnzf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2ljbtvavk.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcqwowld.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gt2owabbeaq.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2alhmtwur.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2ihkaabhl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqxcpspj.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gt2igldhgxl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gt2yovdaquy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gt2vhxgixkb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gt2vsgmgjgd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2dhylgpsx.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2ohwusxfn.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpudnhga.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2umwlujca.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gt2kcvqgbjw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2dujhmgkg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azebwgrm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gt2sgmtduxn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2hkahompe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gt2knzyfjqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2myydytap.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2vlltpaeu.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2lfplbqil.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gt2fhmzjeul.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2vkircjoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2qzooarls.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2ultctwis.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gt2xkpvhcfv.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2xyhgnqjg.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2urdxcjak.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gt2nchlyumr.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gt2noouzqry.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2hoohvoaq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2wllyomyj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2lukyadof.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jicmicdd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2uiwyrwsg.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2dbvernrn.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gt2mxzozwqi.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2apwdzrms.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwieqgfj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2kayqexvz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2zxlzapti.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2fforycpm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2kyclwwdb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqrdiwmg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2nhgmwtyr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2uydajscv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2kcjjegzi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2gqbnemst.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2banjtzxy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2schytiox.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rmdjiset.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jqrhzubf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2djsiyqns.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2vehbrqac.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2mpnrmwaj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2yquqbgtv.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2hytzyuhq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2zfkbrrdw.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2kphnzike.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2nfjdmgts.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2sgxbdlfe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2jhrtxmai.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gt2nvdxbmxz.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gt2myifcvdk.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2scckcwmb.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjbplows.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2gkajrqne.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2srvxinmz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2lnsdtref.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2evuoaynk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2oqswujft.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gt2qlvkpxbp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2hghtxcvs.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2nokyfhns.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2odkzqzdp.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2xbrytbks.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2zhhbrzyt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2pjhzbzhn.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gt2xwmuevge.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gt2oeoyvufr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2evxduivz.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2djovrpvl.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2acbvqzss.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2knguiaqu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2tpzjmrpt.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gt2mehpsvxy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gt2yaessjqf.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2lbbfrctk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gt2iwyqygdc.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2pcqqpdvm.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gt2xhvghhyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2niwnmxgv.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gt2juuscdvt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2ckkvwdou.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2zzedlgmu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2tfbylilw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2wlrgiwju.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gt2dghahlfz.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2zmsoufnc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2tepgfade.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhvhfpsd.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2huiwebcc.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2gjgpwnev.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2nicfuiik.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2ymckzfro.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2adccgndc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gt2zzxuseyi.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2rsserovc.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gt2zzrzesaf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2dpxdifis.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gt2scyndclj.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gt2zqetiuwn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2pejtrvlp.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2eqtqvbls.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2kkuueydx.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2snkkzcux.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2wjcydqws.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2mwzwanmj.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2obygxqfz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gt2zrcrqxhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2jtxzfkwi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gt2fnqvjwxk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qlkfaock.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gt2mlrwvgvh.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2shiqskkl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2hqqecyzk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2ggxgkjlx.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gt2hixyaevz.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2kzhqciji.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2nrkgeigz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2blalrkrf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2czawlsen.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2ipudczpx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gt2tcuvjctx.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2rkckmfuj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gt2zqmwqzhu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2koqzacfr.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2agtpliom.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2dppvogzm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykwnlbwz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2iehgjfjl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2dcdjgvrh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2pjrqlvye.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gt2hzsnyxbw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gt2zgzixlbb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gt2afygxxzg.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2wghuttfq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2shzbokaj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2hvxqrttt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ojimtcad.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gt2oascaovt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2wnpvvdxl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2aqudxnan.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2urzwsuis.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2zjzxtnfr.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2tsxoedvl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2biqmocrs.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2sbqiyank.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2gtgqwnqa.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2devtvjaw.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2mkeocrtc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2zjflwrvy.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nshkkecl.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2hkawwzzm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fzfictpr.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gt2wrtqaboa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2arqnjlan.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2hmtekqef.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2lcpujxqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2dolsoave.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2vdvojvnb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2vhpkbynw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gt2zntnxznv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnnjjmhm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rudnmgbo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2psewnyjf.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gt2hwkflliq.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prhagteq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gt2fmowmzvk.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2glafxpze.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2bcabmugz.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufmjqsek.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gt2fuotkmdd.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2eukxnjwj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jykguhmk.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2eivyeqmc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2fwgiznkc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2jaitmqvp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2mbxpwdlx.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2jtoelnvo.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2wfyozkaa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2rpqtrmjg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2sxfablho.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2detdsisi.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gt2yhcfnean.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2suigfdti.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqnxijww.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2anvhxcim.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2bvtxflos.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2ujsfghco.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2hnooxboh.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2moketwyc.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2taltkyip.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gt2gxzlczuj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gt2pmwrejwf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gt2pxterrev.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2qaonhzwj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2kfkhcllh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2irpcdurj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gt2ufunqbrb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2szrraoml.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2oyvlrjsv.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gt2qevkergb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2wgxjbvil.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2uklhykrf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2iivzimox.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjibjlfw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcuiahgu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2jaajzsqo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2flxsoriy.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2rrvpbefi.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2dldptkru.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gt2jzifcjvg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2mveopijb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gt2beryohrr.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvspqajt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2ahhhytpr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gt2wvvtmblk.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gt2pgoguymz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2oawxnlcx.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2tlpayjmo.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2qwzapmqa.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gt2kylsgpgi.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2gkzyovuv.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2zgznbyub.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2orwfqwda.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2vmcxnukm.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2pbaojbtl.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2jgilhhzr.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2xgrbdtrc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2ntpuavce.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2lferappl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2wxhkiwmu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2zhlizbmk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2nzfpidjf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2wqvfuwjh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2fibcjxeb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2ndkfxmyt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2ponrcsjh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2vfikghhj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsejuzpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2yykatyfb.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2pjzfrvnu.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2szlzmkuq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2rmrscily.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2sjnphyki.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2jxgqkenu.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkuwgsf.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2bhsbnrbl.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2mzjtsndm.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dodelewg.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2cefxlxyq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2owkfgxkw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2rqhixqle.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2rqfgnoqc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikfhanzb.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2govqrsvo.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2fggvtyqb.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2htcsqjuf.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2pvatnach.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2dxkeonph.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2gduhxvlo.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2ugydsmvm.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gt2gkcuqvdl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2pxnqrwoz.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2jtbkomgv.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gt2pmoewsnq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qovuztfm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ggzotijp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yzdfzvmp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2reclbljf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2ziufbjke.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2hnsbfsnr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2snlzorkt.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2twdsgwpc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2ejqwdaqq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2mtqmlmvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2dohyrpfm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2xaeucpbr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyxlmoju.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gt2kscqbmic.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gt2hvdlejcr.html


<!-- 参考信息 -->