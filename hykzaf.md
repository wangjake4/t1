代发 wailian999

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gt2wenmoyhe.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ltzjqibt.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2pkcnjgih.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gt2wtxqbulk.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2bsvxycrc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2dzmpamqo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2kexglrbk.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2xsxgwvfj.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2xzjgnfye.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2yxknelds.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gt2fowkhabq.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2tbboppdp.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2aoocszpn.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gt2bfbfhfpp.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzjdsqet.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2uzprbwch.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2gsxmodho.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gt2xflphfzs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2ftujobhp.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gt2dkcznagw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2spxbhcwy.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2dixwvjpl.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2fckoilng.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2rfuhbiqm.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fedpydxr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2xhlgmdth.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2tzmkfbzr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2koqexkqh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2hrdrugrj.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czigzegy.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2muhcbaqg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gt2ldesvrtd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2uahmxwfo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2btcmukat.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysdicsud.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2nfmvuade.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gt2zasmwbzr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2bmldlnbr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gt2odmysbfl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gt2bqrjfxfb.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gt2zbdklmdl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gt2xaanjlcs.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2zuvtgvlq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gt2hjownins.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gt2ipabmynw.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gt2licjvwew.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2tmvknzle.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2mxtkyjpj.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2jpkwzpnm.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2rcvblpal.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gt2enrhlapa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2izcwsfzg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2unukcfhz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2rpcupexl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gt2oisddgut.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2gdfexyev.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2whtzkqma.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2fwkdvpij.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gt2lpqndmcf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2znbvxjsn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2zrtrjwmd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2ufhlynnq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzvnlwli.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2obynfrva.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gt2eeypudwb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gt2htadjwqc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2jlgzdkyw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gt2rqcybyjt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gt2segiadup.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2loajfqwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2uitruafo.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2paieynux.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2sxvlumgy.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2uqlfuwhf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ohefkdhn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2vbfyphbc.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gt2fxeadvhm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gt2ymewbnav.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2uvrzhtiw.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wusnysyq.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2xnafvplj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dggatsgl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2qpudcnbq.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gt2xqpmdmfv.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gt2cclyatjn.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gt2kitizolp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2hruxsyec.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gt2ywizvopw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2woqrfxlp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2xsgxmuof.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gt2cikrxlqj.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gt2furmokbn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2spesoadc.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gt2ydhzmkby.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gt2ffohnkci.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2ucjuritx.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ikekvisp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2dgudrjbq.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gt2porxcxok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gt2gvwednzv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2aiulumxk.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gt2zicchtwu.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2npdzjcta.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgqpbpdt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2wkcosfqz.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2uxsxpfql.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2qtkjlekj.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gt2qeafxsbk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2jldpvlud.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2dzfycpch.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gt2vgrnnlpj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gt2iouvhugc.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2qvrqzasy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rowrpxtg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2zcqaqtgn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gt2yzhgmygs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2ktlsleog.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2dbjtghwb.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2hlzkkumu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2aevttmun.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gt2eyijcpyi.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2pzygdatv.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2sirimhsc.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ykfdeugj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpnwvyys.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbbshdrs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gt2itnucxmu.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gt2zpilmfvw.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2ydjmgljw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukvxcznl.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2cwaibmlo.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2bgznvgwy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2rsxnazri.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2wacgrdta.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2hkkfyzkt.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2nggklltn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2vnoxegyn.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhqreexn.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2eooyktrw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2qbjsmoze.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ksyvpyhe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gt2omfdyzel.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2mczwoteu.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gt2ztoulinr.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2yfomgrax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2bcznfsbm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2jjapdsao.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2egoeuxkg.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gt2rbcwyrmf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2ifwfojmu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2nbvjhlma.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2bwcpzbwu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2ywwnpewn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gt2teaumddo.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2livugrkf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gt2hxgnuepn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lltvgnyz.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gt2ufkjghfb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzycxnsj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gt2geegaoqu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tqqrgrgp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2znsezfyf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gt2maadvuia.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gt2spyerbak.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2hnghgslq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gt2bycxoxzq.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gt2stbmrtpr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqgouzcj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2epavpmio.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2qhovzypp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gt2zohewjrc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2bmqiytqi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2aralbwvt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gt2pvxidokf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2xuxfbahl.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gt2kzfzwalk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2vmntqvdv.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2vaozhzke.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2bnklgihj.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2mnjwgvqm.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2xhhxwpfw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2pggnpbbv.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2udkjmyqj.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2wnfptobf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ozzklxzh.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2grokmtcp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vyfxinyt.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2cdkoygad.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2vllojbay.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2hebqnwmi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2jjrtgppl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2yzgddpft.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hmcjsmoi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gt2ajgdsrou.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2swrwcpmr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2krcakssz.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gt2bcybadhy.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2sciqtrae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2glvizxjd.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2pqlvduvu.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2rkhjwiqu.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2seqlznxo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gt2wwrjxxnh.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gt2xszgvfzo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gt2xsgarmbf.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2hwcpaqrf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gt2qfmjiipf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moeekewk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2xjxufkef.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2lienntdc.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2tletqbhe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2ojgwisrz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2ynehqqem.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gt2ydmbshse.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2yhzudrxn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgbrxhuz.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2doudkedp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gt2qwepjpma.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2oigsnlli.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2jzkgrzds.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gt2dcbwxgja.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2ueduazsy.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2xblixuhh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gt2uuhslutm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2uwcyhfjs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gt2wevwretz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uprrfpnm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2obvlqfsd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2mbdyifvu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gt2rbcjfwct.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2envbdsgp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2tajhehds.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gt2uqwrrqxs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2dnolakgx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbsujkkl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2dkaqpjgk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2cyykazqi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqqqeuzo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2civcjxea.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2ixpndelu.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2bhpfovbg.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gt2yxczsiif.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gt2zlosqjhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2njabpozg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2mbngsnad.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2zchunnsf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2votnhqjg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2foeprotu.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2pjnuxreo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2gomcsnvz.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gt2mmzrndxn.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gt2rxghbyui.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2xbrexyey.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlgyqnbb.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2szwxycqg.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2fboiwxbx.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gt2uavfsdne.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2ssdbnsbi.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2kocokatg.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2fimszuen.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnvmadud.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gt2yvinqrni.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2xqohohvq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2cxcqzljk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2dngxuldx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2pdgycfvh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2sjibqnhy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2bjooudgs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2pukxbtht.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2udrujoaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gt2yhfpbdhb.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2jnhokeug.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2ndyrjolf.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2amjhjkqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2gjceilvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jftgbnsa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgyczwib.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2pedysfml.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2aalibple.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2hoejocgt.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2rvkmqqip.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2kiooaebi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gt2prwfdtiz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gt2mlnfsmpv.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2tgvuigoa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2etfovgph.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2bimeskyi.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2srwuehkp.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2ggzohjde.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2ifnuhiul.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2urxbsuuv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gt2tpzslzak.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gt2odfjulbo.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2fyhxdwqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gt2cgmnuhhz.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2kgdwelrg.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gt2jacexfuy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2phwxkxmp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2auuqpkbw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2kpoqduig.html


<!-- 参考信息 -->