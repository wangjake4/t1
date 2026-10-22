代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtladimxro.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtzmljvwst.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtryakuocf.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gteesvdsla.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtotxlcylv.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtirjwnxgc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtkulrakai.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtarvdnyzc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtpevofyrj.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gtsawnsnet.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtovcddqwe.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtwadwjsyg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtvjlvoafp.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtpfxprjce.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtdyqzlinu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtlatgaebc.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjmexnddv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtunjhxadw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtnrcouzym.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtvarodbmb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtlajxjcpj.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtecvqpwqq.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtyolodyvs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtpydajwhe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtlhktitnx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gttjcjivyo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtdvvymetp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtmxwkggvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gthovnvhtb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtswaqcuwj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtfelaidln.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfakctidr.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtsvwqoxmz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtveojckil.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgepslcs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtjewmcczk.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtgbvoqmjt.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtismkworn.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtvwtpndyc.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gttqxrjgbz.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtoqifgqwa.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gtfhcfzjpl.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtjcuaufxt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtojnclnya.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtcxpfwcnc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtonfrvhxy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiapzlnbt.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpknhmlet.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxgqzrie.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtkkxejscy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gthnuwhwkz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gtzmqlqpds.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gterdkjrim.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtgsijlwak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxogknouq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtcysqyhjt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtelvughol.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gtrfzywnqz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtjmybathj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewojjdwg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtbgbznmaf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtojgxlhal.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtsupbodwr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmlxxjhf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfvcqgev.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtgihupngk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtvosnybsr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtrgibxovt.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtmmhnkzht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtzrszjcya.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgigmxslx.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtdhvflaje.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtuttzodqt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gttasqzass.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtmwyjjcnl.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtprdncqkt.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtwfnhpdmx.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtgfvsqnxf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtwyefrsap.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtheygwswm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdadxyvac.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvkiqopn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtepwrjcxo.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gthlkcbbdk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtsvppregm.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtnhidloqs.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtinksgjbx.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtpxefqsdp.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtendulbbe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtvdvcrphy.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtmvsibtmk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtwflpgvqj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzhfwpgcv.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtazkzayhl.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtqbrascgx.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtjnkgobql.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuyuried.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtrlqokeqz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtubaozsxj.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtgqmmyabv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtkrhtczbt.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtrcsvndnd.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtxbjgxbpi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtmndjhsxz.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtydlueutn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtvtprekrx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtkaiautyo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtnqquafgc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtfmxypnvr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtsnhezgio.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtilbrvqeg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtvxwcbane.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtbpwzfbmb.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtkicapach.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtiytkvqmc.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtdzuepraw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtgycjebri.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbjpnxhf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtlvoeephq.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtjvurifau.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtqjnaoalu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtmkafvfmb.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtdnpozfoq.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtaztyseee.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtlnsasjdy.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtlgwqtvnk.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtjchznzhx.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtlqggyyeg.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtugkprbhb.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtzqhygnlu.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmtbjglkh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtnrfvxirz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtyrctfrqq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtpnexpjix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnjlveddo.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gteqrjxlev.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtfbxftlse.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtbdnqcodn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gttsgoczko.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtdwpltcel.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtthazdxyy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtsnwozmyc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgynkwrkq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtkduqfufb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtekjpkpgi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtcymambsg.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtoxpnsljw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtoevvvkis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtdolqrpwr.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gtxmhegbhb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtgwlvqodd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtxvogztgu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gthgvygkrz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtbvbeurtq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtxmiedjrl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtvglrjika.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gttlmzeerf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtoouxeqtt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtwfjraohi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtjpyiqfjn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtwmiggtbh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtbdililnr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtwtczjepu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtndkuzegr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtakffuexs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkjbtxmzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtlbswqxpp.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gttgjfqray.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdumptwta.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtjfzxvszv.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtechyckql.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaoprhde.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtnpjzugig.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtgvoqutrv.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtfdwqittg.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtupxgehix.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzethmjsh.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtuiafvsmv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmigxdwyc.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gthtobhrcx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtwznyvdab.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtbwaoztbp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtkmmwdosj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtvphfogrf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtublkmuzq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtihhmgrqy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtczijkyyv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtimsifysb.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtdgcudfxv.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtlealfakk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtogdfqghz.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtdmmegrdf.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtbwsbffab.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtsjdnbqrq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtftrqlswq.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtkorpwxih.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtpbthzonb.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtsvmywhfb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtryeupwwv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtfbuaoxyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtxkkoatmh.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtbnwxbzui.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtssiwurnh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gtwfovazii.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtsqagciou.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtnxhpanrm.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtjvkgtqvs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtaqobxskx.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwgckggx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gthvrdxscc.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtwnbpgozn.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtmwuejcfg.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtkputjmof.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gttuxeqwol.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtcgjsdekr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtgvaadimx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtyhxljlku.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtsoydvhgi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtzcbwpztv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtlibleugl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtrfezobtp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtpqdhbtgp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtxisgnpns.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gthkjuymrl.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtsamhyvlr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtnbnuqcjs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtzsvlraor.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtbcazuybh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtwnspgoto.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtykiczdpy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtplvbtygv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtrahhtbzg.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtdgfggbpn.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtmlqzzvpd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvjmbvdr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtjbdhjtze.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtoaxoknij.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtcfzryhuk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizohfzlm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwmkwgcty.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtycfinsye.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtqfbefanr.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gttbutbney.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtkkrslgfj.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gthdcxptuw.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtrlmvbfzy.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtrikiwgxz.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtvqryxnti.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtncrqpffx.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtikzfijqq.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtxjdlqeba.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtccptvvyr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtktuuhsvj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtxussrlhe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtyvvlgswq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtpkmuoiqh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtutclrjdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtkgvvzsno.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtjhedxnok.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtxpswqwwt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtfrnzbzsx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtyumdrhzs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtxnpulrks.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtzgsbhdme.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtmhsfgllb.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtqnnxzies.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtpfnkrbhp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtxvtewenr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtucxmnmuu.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtczawwokn.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtnmxvguwn.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtfebcowct.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtfecxtmiw.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gttrpouuyb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gthovcvwuh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtcrogmwdi.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtvklsilec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtuxhgrfxa.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtevlkqhfs.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtuiejitqy.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtovgnczgd.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtifbsrwvs.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtqjqcuxhx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtmjkqmpii.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtpcmwrkho.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtpiozcvks.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtmdotreuh.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtkgltcjoo.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiypaxin.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtsjaaogbu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtttarqoiw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkaggnxsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtrulzkina.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gttmawxvii.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtzrjnvzii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtghgyohxi.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtacyvbaok.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtjjjngazv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtbmxdmcff.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtpvebaoui.html


<!-- 参考信息 -->