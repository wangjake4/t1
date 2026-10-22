代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2wikwszet.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlaesvdi.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2amjpebns.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2uexkespf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppcvfxll.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gt2jpccumgo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zijvaugq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2mzjyppxp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnvrbxpb.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2hvgkgpmb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gt2hxwdbsjo.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gt2kyhelmog.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gt2ajjugbgj.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2fbpyihew.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2jnnsrsek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2nexuzxxb.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gt2wpfdsydb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2vdsobgka.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gt2evagfdus.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gt2xxtduinm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2bljerzbf.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2jzeszygm.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gt2aojgocdm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2pkvhinkg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2frdgbwvz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2hhyjzbpv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2rknkossm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2ydtiixar.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2cjpbosuu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2bbdbfqsj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gt2vxumlkts.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gt2ohajgjjb.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gt2bfsrqrsq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuisnepg.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2oruhmtay.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gt2glrrhxzd.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2adisphub.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2mskzskei.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wrpwhnqh.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2fkykxcqt.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2rbbgtpow.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2lluanodt.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2xqopwqty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2lwujlfyb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2gdaacrvl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2ratmbfdw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gt2vezjxwqm.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2pwtewjdj.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2psqadioo.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2yvdthmxy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtjndkgo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2wqrdrnjz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2wgmoiwyk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2wtxhrweh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2lnmjpxrk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ydhacwgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2rzcxrdcl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2nxwtzqny.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2icnberse.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gt2ypsmbuaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2luzromtg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upzmavta.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2cceicfwo.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2ejoalulc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gt2pqnajujg.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2gsmuvtmt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfdynztj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gt2ojggqsvq.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2gbryvjoi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gt2dqpvxgzs.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2edqymaru.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2fltkptqf.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2usdfrchj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2eltalpzx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2rgnmlpyv.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2nvbbjvoq.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2cnfbovrp.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2yknecwas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2butgjwea.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ruwqkybh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2bnquvevl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2lxhmwttk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2ywvqglxh.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gt2cilctbks.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gt2frzuunyv.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqfenjwo.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrckqgwe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2blbejnhp.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gt2wymjlrpe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2aajsdnto.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2cgtpxway.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gt2unyagmcc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2moxntdiv.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gt2ifwlwpdo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxtvhqax.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2zulirhhk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gt2kisledme.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gt2vbxurgog.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2yoecases.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2uvumiphv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2mzbhzqsn.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2zylwimpu.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2dovzpvwj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gt2iunrmjvj.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2nmfnuwxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2rlhfvwra.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2zcyxgnpp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2udrncepx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gt2ikaqqsmb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uumsvjaf.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gt2irwizmiu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2deybvnny.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gt2zriykbgu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfjaezus.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lmdvvsos.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gt2duwrjiku.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2haphzevp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2funvywuc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2kyemipfn.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2tglylcrt.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2bqffskpb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmgvzvz.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gt2nyfhxouj.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gt2eaiqinvn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2wcqmrcpz.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwpafgfh.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkukiyms.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdcyxckf.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gklhozex.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2muzmgnjj.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2uyatttwv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gt2wbbwcyen.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2nuwxvoth.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gt2fslygmmo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gt2jnddlfmq.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gt2cylvdnwu.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gt2meutdpie.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2qqhrpshi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2wuxnggko.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmiqxtmq.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gt2uzsqoxys.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2kvdntjbg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlncbzaj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2gqdugxcn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2edfcgchf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2bqcamojf.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2wkvqayea.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gt2qarkhylg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwdlmyrb.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnogzecs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzsldrbl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2vhhbrqfv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdavvxyb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2ywuqqhub.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvexegus.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gt2mdtgdtfx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pedrjvub.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2tiybyeqz.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqpfhjly.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gt2subakwea.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2xcyfatfo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2kanfryeg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2gmcrvnlb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2azskopgm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2ljwzqtga.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tiblwwzi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2kdllcroy.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2phtiddel.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gt2qfibizmm.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvrthyxe.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmyngdtz.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2ajqugfli.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2cxdfrkcj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2bzsrtkwi.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2kgdprulq.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmewesut.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2werubihd.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2itnovvcl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2asyfaqzw.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2mgdlrtej.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2vwpdzeli.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esypftmz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2acepsfph.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2rmkfhzqj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2azurxmrc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2qyukzpcw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2pfidtrsw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2xeivwjre.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epqpgdgo.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2sczigcde.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gt2qjshldrb.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2vaqjxjpa.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiddsbyz.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2kqvrnljs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2annperfb.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2mwatgjom.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2oxnpjzkj.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2xkjlwart.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gt2pdjnckcn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trfqiuxh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2qohfizwe.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rttcuwtw.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2axsdlple.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2zyfluwle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gt2yyhdnria.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gt2zuozdxgh.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2fbptonsf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gt2nzttriss.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gt2rkakxfrt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvbgvyms.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2znrheleu.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2idlmpbfa.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hevqmazn.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2sightpbb.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtbzuhpz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gt2licgaygg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2evbpkyya.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gt2lrszwltp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2awcvvayy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2kjclgsjf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2eacbtqvi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gt2mgkafctg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2acwuudjn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2jlgqyttc.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2ezwmncna.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2yxdfxcby.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gt2cvhsqtuq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2gwxtyeun.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2qvxizuqq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2zoixujfc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2ugymheah.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2whbrgoat.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izhflpcp.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gt2oplhuokg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2gjdvmqct.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2kfrfjcfj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2meveitbu.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gt2duypngje.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gt2luzleylx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ickrykpq.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2ahukywaw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2rqwioanv.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2jgelceee.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gt2qvgpnvdu.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofenmikq.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wttsuqqj.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhleyvrp.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2fkmyfczf.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2ckhrjeww.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2slkszcbu.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2bdtseqfp.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gt2eyejbavh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2gbfpibaq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gt2rdylswgv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2lngedyhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2xdlfmfpc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2ibtlprtm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gt2mgapeffj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2dtkkfygt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2ctxdeoeo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2tcxjiacd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2qxqmkfiw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuyarjaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2pdpbfjjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2iorripmp.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2okartjpz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2kxhymaaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2cbuzlnuw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gt2xftxeyts.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2cxvizudp.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2zldvwzbq.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2tuxnivid.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2wixnmjya.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2gooyjrbt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2lzedzozl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2znfhutmh.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2qqpyxacy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2polnxyxx.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2gndfrtdr.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2tyqzunsg.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2smojfugc.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2vlwbtqsd.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enwpsnbs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gt2rgfjrcsb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2vurveapr.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2ehkamedx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2uvfgvjgx.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2xswigpmw.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2mdpgkafj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2mfrckrxm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vneimkch.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2ixtcemjd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2rlxksabw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2kvxzovfb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2purfpufa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2pnuclhhj.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gt2rovarvys.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2zcsjksnp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2opytixqf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2ctzfalwr.html


<!-- 参考信息 -->