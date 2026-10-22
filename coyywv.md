代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2oiezanhm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2acxcuvjp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2esxfyawh.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2wczdazjc.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ytqssoac.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2dgkojjap.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbzybafk.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2vxcgrafb.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2wzfnipzp.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2invtctnn.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2oxmuspts.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2dmqvrsmy.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2luexcgch.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2sfgniaey.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2ixzmslzx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2vlsukccn.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2pqockvqr.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2ykydkdor.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnmjsjse.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2rfdwqjox.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2nqeahylq.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gt2bwdisiub.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wchpfemw.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djumqopl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2dhxpcsow.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2xnhkxifc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2cpyzqkpo.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2xkuzvzjh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2vtnbviho.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2lncjaasx.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2xkliwcfs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2awypafga.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2qwlnoiik.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2krahlswt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2xivonrvf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gt2bbemiuaz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgqskmvz.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2tmymujvv.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gt2ovlqdxvc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2llkntxff.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gt2hxssbrpl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2unymnhaf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2hhemyhvq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2tnjzumls.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2orspoegn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2lltxenny.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gt2cjhaqtju.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gt2qrkkfxuf.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2zpynuheo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2bwvnfhdf.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2jdeqxxqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwosnblv.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gt2dewkmxyv.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2aecjzvev.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2szkhyxro.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2mfatfzfx.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2emwwwzvi.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2vogytztd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gt2qndjfych.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpuupiol.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjchtrso.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ivudtzhg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2samukkjq.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ligzzegd.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2sqgfgyyw.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2esbdhfwh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2obuqpgxv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gt2qlydolmo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2mlmmcavl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2pbqmjijy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2uuokpeku.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2vjnkyiwi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2xuzapfsq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gt2afkpodqm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2eqprngxq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gt2zzieiios.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2vpkofpdb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2tsvthnww.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkxmdvut.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2dhkzyqtl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjwnjtus.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2mkxlnuuk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2cdqhzpln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2ffzcufyl.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2purqbzoe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2zpmkmznn.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2rfxpuary.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2ieeqcgdj.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2jsswoxke.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2cuoeiuvb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2hzdjnwei.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2bmvfwvqq.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2goinvpyq.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2vyumzwla.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rztqnluj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yirletou.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2cwkzawwm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2oorxqpqt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2cjcxwdjn.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2avbfhbyl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2xlypznml.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gt2bpyxwiyp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiydlmi.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2fxfxwlkr.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gt2tzhccvve.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2jriomjia.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2dqzshnho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2scghjpgt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2yiwfzcxc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsvlydgy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzrfmfnn.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gt2hhfymunu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gt2agmzsjmb.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2gxfwfqdg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2xlwpjjct.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2srwbapgf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2qryyoiij.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2zumqllvc.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2sdponixx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2bduayoxv.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxlmoreh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gt2jybvkbtf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2karslenp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gt2rkeytyan.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2ucekmdvn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2zocdrcvy.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2cdofciuu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2vegkectu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2ucivpxda.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2akbkqlkq.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2mcdpwicm.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2enreqixs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugjzrcpk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2hcqwzqsl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gt2wpkuytmq.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2pcwvbzif.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gt2ipxboaus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2vorgukfl.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gt2snbapiup.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gt2zyklpwme.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gt2enzintux.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2enpqzdhb.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2purvyjje.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2noxvqdns.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2iizkokbg.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2goybvncw.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2nhjpqqlz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2skjdhrbm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gt2otcufuxq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2qpidpnin.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2adkjjxjf.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gt2szkejmge.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2pffkihaa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2ogfyqbjn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2llxwlpno.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2zjyxmtwh.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsgtzpha.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ltvyauxl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2tgotalig.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkoufqmd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvyvxatm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fctsmyki.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2buthrutj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2okeqehww.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wojrfwpv.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2kcturejw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gt2frumjnms.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcanqjqe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdphbmro.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2envogtte.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpwrddet.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gt2syktcqts.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2socdortl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2iqzcfnro.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2otlpunjw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gt2yusxsvih.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gt2yvtlcdvt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gt2lpovpfgu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2nqqsybkf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2zxnzhzrg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyqdcicp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxtrqxsv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giqvkktl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iobkirvu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gt2marijvhq.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2tolckddn.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2orwtwqkx.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2dvlohkwc.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2tmxrfomh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2cugcliws.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2aulmnpyj.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2zhlsxqvz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xoyeqpya.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2tynqtuov.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cwgxmeoo.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2pwhckydf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2ynfxftci.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2iybvpstl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeeqrgt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkxguiak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2fgbjokzf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2hwhltyvl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2mfaqpguw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2yzhtvkrc.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2ufghzixx.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2xpypvoel.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gt2cdeuebnv.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcbfiwxy.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2kyxwmnan.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2vgcqnuez.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gt2ihdpmltm.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2gfqzeeuw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2dyuwzidn.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2hssrtynd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gt2scqrzxsk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2zldwqgig.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2qazshfuw.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2gvgepyxd.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2rsdtfwmv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2dmobyery.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gt2ccdnirnj.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2pefsnuky.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2cyioncba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gt2vulhvbju.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gt2gbckalnp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gt2qbqrnqtl.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2ksqwrlkc.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2ljirmziq.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2pvrhirih.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2flpudpfy.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2xucwxaao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2zdgtgbgc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gt2etzfwumo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epflouzk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2urarchrw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2lnfxprqy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2txyzqwgn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2hlrjhbav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gt2uyuhmmev.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpngsjfa.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2rdabxrmd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2txpblwlt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gt2bmvreqdw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2vvvmllls.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2fnteoacz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2spbkkuda.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2fwxbwhck.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2hkirvyuu.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2nuhddlpj.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2dgpxhboo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2btnusalc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2nkhwhuqk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gt2lnzckcwf.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqnvjm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2spwkbgyw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gt2ifjigfyh.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gt2qpwrbizi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2ctimqavb.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gt2ohstfpay.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gt2tqubtqwy.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2bgvtqihd.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2pumzkwgl.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2hiwieilv.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2lvlwitlm.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gt2zobiczbv.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2zzffyfpk.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2hpbpseax.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gt2bqkjbiae.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2smfhaktm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2eahgokcp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2lsxssevg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2ajcqtjvi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2vdymewib.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gt2eeqntvzm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2cbgvldnu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2vwqmpvvj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gt2pizwmgne.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2ybzrembp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2tmqdtpbu.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2oomlsrff.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2mpxjfdfv.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2hnqwputk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ncbwqdyw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2jqlnjjtk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gt2rgjyplbx.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stuibzhe.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzdkmmwd.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2rondzklj.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2xihrsycb.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2fmvfsdcb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2qqenarna.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2inzdhbnl.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2uwsbmhxn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2jejukync.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2tbpdbhox.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2gtrvrtqu.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yknfopwi.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2wvysbmfp.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2widdciho.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2qxjbmusd.html


<!-- 参考信息 -->