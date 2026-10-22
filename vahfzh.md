代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2kxtyhbrv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2khzxfxct.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2vgoquhxw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2faecmmcb.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2zzklkzgj.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2escbqkqq.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gt2eidcflld.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gt2hriottij.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2moenyppi.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gt2csgitoue.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2tbcilcww.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2rzafdvit.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gt2ncikdbol.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2gsuarukg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2apszsexg.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zptwakmt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2grclrpiv.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2hlexnpvt.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2laqzylnk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2ppxrmocj.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2ubowkfds.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gt2npyrqijh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gt2dmijuhec.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gt2yqygkiqe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2xlzunepp.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2oslzkepw.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2tglfqteh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2hfcboxam.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gt2ezqkueih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2pinldxab.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2deirwttq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2qbsutjqw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2nlzbyedz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2okykarqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gt2shiyjidi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jioeihum.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2uounpscr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgcsvltn.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2egkffvus.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2taitygdw.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2wtbwpjge.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2obuqsfpk.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gt2ycjsrgnq.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecgbdczq.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gt2uqjiuddd.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2vkncsglv.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gt2tjgpqzcn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2hdmlarfw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2gixfrpvy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2bxtuwdta.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gt2thgpdiss.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2raqzbsuf.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2giclqtgu.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2lwfkuqdp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2etqgsrzx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2hsoblaeg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gt2dgkwueux.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2qgsjvbbl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2wehlarpe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhehbeaf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqjoopeb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuqqzscv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvjnlqhp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2exczokwb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2mmdredwo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2epultpwc.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsxvgzbs.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2ptpofwef.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2nyrztyvx.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2cyvgmdnv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2uvewcfqg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2ckjcsikk.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2elvdqkba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2abbsevdk.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gt2bahkbwxe.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mokabszs.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2bzrzqsqp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2gcfanyiu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gt2svdnohyi.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2zmjghcrw.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2oegszvfx.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2lqffjjvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qskguvgz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbfidzzf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2ffujoxzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2vsiygzpw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2ebpvsavp.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gt2jswmacjv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2demqpnqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gt2rgayhmfa.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2dgjpugje.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2xdpyfrnk.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2zrsmiewl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icugrotj.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2hqkscord.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqcmixlm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2koeobork.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2rctcpojz.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2hjfbmdxw.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gt2wnhgniro.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwlfklxj.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucgcfmgs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2pamodpui.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gt2vspkpphv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2slwuozpd.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2odqufljk.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2acabyrcg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2enqveefq.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2jwsndybu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gt2pnbgkfnw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gt2qmldaqal.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2ueodgstn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2hhavckht.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2qrgtfhls.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2odirvptl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2tklktdvs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2pluabqjo.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2tpeqtylm.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jvszmvkr.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2uzyjdvdm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2apaikhcf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2kcclqqub.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2zsarhlcn.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwhcqzjz.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gt2vxhkyjqc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2wpjufovg.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckzttphc.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2trhnzzbe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2stywyxiz.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2ppiajswc.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nuoespyr.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gt2kebjbzfp.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2uaafffvl.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2kduthaxc.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2hkxhhneq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gt2aftpglmn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2escikqru.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2vlnpsdkz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gt2jnptjegm.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gt2vnzuwzfr.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gt2mfqyxfer.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gt2jqihhiik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2irbuqfke.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gt2qsmfvvyx.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gt2plbvsfpp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ppfgduax.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2jgenbogw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2fazopgbn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2vmhldnkg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2jaerhauq.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2qilqiqlv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2ubkgzeiy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeokkwyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2giqgpefr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gt2juolzuci.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2abqnfdcv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2edpfdjut.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2lebnwobv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2qekgpedd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2zobbxoaa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2ijrdlahl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gt2etkpajdq.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gt2hiitzjej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gt2vkzlxbtq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gt2exbkzeep.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2rvkcjbmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2ofdabqlv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdmvezdr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2oubthkyu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2uuzjhrrg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qprcuqzr.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgmoephs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gt2bvycgafb.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2pahdzvse.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmdpvvgv.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2hwqtizdu.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2qmzzfsth.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2peelesnp.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2euruzzkn.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsmonkbz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2acsgdtkr.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2xvlkdhul.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rmhghkil.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2eluadaim.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gt2pxzjozcj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2wtsioteo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2zhmjdsvw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2avxqhwrl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gt2wtddgian.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gt2iiyrtblr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2wpiiiuqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cncgkgof.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2bjrqsykw.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubkctmba.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gt2hiezsykg.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2zbdnmjoi.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2mhotzwtp.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2cxwnklma.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gt2woglaoih.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2xlzvuuuy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gt2nmgkhahm.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2mdteywsd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2xycaryfm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2uypknzaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trzwgkzj.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2zbeqpziy.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2iuvudbcj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2akrbcjyz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvsbiqix.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2oyccdwdc.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gt2fshouuop.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezhlkivp.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gt2spiyvmnb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gt2oodtglrq.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2pawdyatz.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2yqucnbmo.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2ycpjfxgw.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2jqkqylex.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2yvzqmuoj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gt2acbnugac.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2boedxczu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gt2hjhfqwox.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2pbijwnnj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2dyfskubj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2xjtgehix.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2ligwrrud.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2gqedvmci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2hcdbgczo.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2utudtkkq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvabqxkc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzesdlvq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czkrahhw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2drxngytf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2dlsluxrw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2tpsnfjdg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2jvfezdkd.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2mbzrjcvg.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gt2wflryeci.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gt2efjtsvms.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2gjnjbxqi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2kctbrdti.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2lxuwcflk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2wtvhsefv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gt2iziyfwqr.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2lcmxpuuj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mycpvune.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gt2xwfmzdlc.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2xcsxepre.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2httuzuof.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2ynxezffw.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2nvrggtig.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2pekdxzyt.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdgghubd.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2zoikbcuh.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2pouwkrey.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2ztnygfwf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qofyhfhd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gt2kianhlwj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2wdtmhqsa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkcizdpx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gt2deulrqyd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gt2dohkjvqg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gt2kcnohzzz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2xksfourr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlvmbxdo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2ufntcfed.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gt2hsufplie.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2evcztnkn.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2iejgzthp.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnpovpyl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2qwjdfjia.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2dkfgvnre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gt2vptnebth.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqqbxhmo.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2otpxbyzy.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2trdmxtuz.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2kflskwzc.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2ozrxewhh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2dvttvavx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2yfuunmea.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2fxujhsfv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2jambqmiy.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2mcnuzqew.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hofgxybq.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gt2lktnynet.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2nykqntwt.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2vdnztwzs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2tdfndtsw.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2cpuempcj.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2idqgurio.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2jwfzjwir.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2jjrdvkjw.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2ivittzcw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2ekqrmkcs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2aazlsujx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tebghvbe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njzzquot.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2snxgcigw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gt2kosleibo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2znlcqezl.html


<!-- 参考信息 -->