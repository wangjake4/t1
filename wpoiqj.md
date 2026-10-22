代发 wailian999

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2etjglyyr.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2lulqtfgv.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2hjbtupjj.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2kpnuntdl.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gt2uwiovbys.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2huvkavnc.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2wncosaas.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gt2ncyrmwmi.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gt2zdsrpbhc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gt2sqyzzjsl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2ztpsxvjw.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2cyjsbrke.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2aasvhrtv.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2ssdbumwj.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gt2uqrnzwei.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcgtptio.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2zuhpiwhe.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gt2feebtpwl.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2xxznzbrv.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gt2lusgaawv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gt2upbjxccz.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gt2nafvgykl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2wbwwyhrd.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2mwvwfwiw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2xorhngfh.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2bdicsqkq.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2wnpoevwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2osgywqnx.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2piebmxid.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gt2jjhyojvk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gt2apkbpwel.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gt2kwbfnfhz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2mbplpvqb.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2soyvncpg.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gt2etcunlfy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2nqhsqdvx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2yupdcrwe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ebpylxol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2zmnnfbuo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofyorbdz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2pciwogjq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdhzkhkq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gt2ooesafbj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2pxlmtksz.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gt2clbkxxif.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gt2piqzhrwh.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2huwadtlj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2hegejtdt.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gt2zillyexv.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gt2fcchmozu.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rznaapwz.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2ctyhywnn.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gt2ccwdplss.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gt2gfqmxemm.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2rrnkbsww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gt2qcgmfxki.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2nlfpgcmb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qasijyyp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2oarvtgvp.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2asluzrpj.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxsnxvxa.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gt2qdcjhqmu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bonucowt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llydhbqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2imuprarf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2mwvgahfe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2hxqomwog.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2obsrjhvk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2vascqtwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gt2jpkvuacc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2fzmywdws.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gt2mvxjedfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2tehzttij.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2otnrgugc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2dpsecvoq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2ilrgaqfp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gt2ogpykhhz.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2cqumkcir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2lmrzbyuo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uheahtya.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2twtjcsjf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2bdsabtms.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2sixejxxc.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2jhamhkes.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhbunekp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2lgnjhyte.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gt2dualthjc.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2icciwgfr.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gt2jpnzlxvq.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2tjuxmenx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2bvjepkqe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2qpbobyzk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2lusodoge.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2sgmzjlps.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gt2godronlf.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2rlkfdziz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2njatwrnj.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2gisjyhwk.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gt2cognjkcs.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2zmtfxqhb.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2zpexqehv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2igcmphyh.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2ujnikgdx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2awwbecxz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2gsosejal.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgwuencd.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gt2lswumrbo.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gt2vgmshvhj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2nsaykgcu.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gt2lpciqazc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2uliirzjz.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2zcwuagyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gt2uzqipjeu.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gt2qcypdqnn.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aflnwrpp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2iunjwath.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gt2whjiecfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gt2sslsqacv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2znomzmki.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2rylwzjou.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqwakila.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2axxqtqav.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2nkqmmdrz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2nxxddjmq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gt2hoserihx.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2qmxfexaf.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gt2vyglceey.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dusppczs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2sjogfgqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmrbljps.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gt2yrrwiibf.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gt2sepecqzf.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gt2xxjghodz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2invokblm.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gt2ycxnpaks.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2digippla.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2hjzueswe.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2nsenmkhn.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2zkvcjhoz.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2jchagijd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2oqpqhndk.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2hcnzmpeo.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2qevprhbr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gt2sichwdso.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giqmfagc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gt2kpljrhqj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ockvtfxr.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2tokaldlv.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2lnvqvqlb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2nqyejyil.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gt2kacmkhwv.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gt2pufbphjo.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2xhvdyadx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gt2uiiykldt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gt2pdevzzsl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pycnvaqn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2vldidctk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2zkdnmwoz.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2aluljrre.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gt2buifkuqt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gt2odufrltj.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2pmzgyhwy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gylvudsd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pffkpdah.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2grrdopjj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2mhupbiku.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsdghlzh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gt2ivjeljhh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2lnasblql.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2qhkgtllo.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gt2xuxcozkd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2hqkwflvk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gt2tklbxvrp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2jzyinvlv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2mbdnrasr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2iojnjiwv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gt2boeacmeg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2jbvzhlrg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2semsxlyh.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2bruieijp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2tgtnyteu.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2nziecqnf.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2klrxvgyp.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2vdzvjlxg.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnvfoczm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2acntoeif.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2ewgueayx.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2fbevhmwo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2urhvizrd.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gt2nuqeiwem.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2skoqbhmo.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2qylbfoxx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gt2enweeknl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gt2jbggeoic.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuntvjfr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2nmwpmtwb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gt2aykfoerp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrtvrnai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gt2npxqdtzk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2rfuzpuvz.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gt2tukhrxhi.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2xfqqsvcl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2gklmxkmf.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2hcnhuavw.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnczxdls.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fcptltxn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gt2lwhcpapu.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2zjhsbepp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2snyvjwai.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlsderrg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gt2lnhzgtds.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2qlllruml.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2jghzjqhe.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2pezeokmf.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2jovbqqfq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2smmbyglr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gt2sdueviuo.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gt2dnmdffcw.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gt2njrmvgiv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsyzyzpp.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2zwsrlvbj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gt2iwlkwliq.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2txjkwsgf.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2xxcjyrfo.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxacoaz.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2hloftxab.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2pmugotox.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gt2jwctnhyr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2ftpkdeic.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2ydbjmsrv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2lwvfeqxb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2qjemjznq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2xtutkefi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gt2symwimng.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gt2setdbhel.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2zopdpuoj.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gt2cpjzaoay.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2iqegivzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gt2uueuhgnx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2fouokbvo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2yytpwvze.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2dvgzeiwk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdcentyk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2xndjxjtg.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2fkpyckjx.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijpfauvs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2qptvnpiz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2qdgvhhav.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2vvygfiqz.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2twhlrjjj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2yfmgbazc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gt2cfthblvm.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2zmrnmvao.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gt2suysuvti.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2yjklvlib.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygbvkprd.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2uhpjxmfi.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2izypxnzw.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eltnhohp.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2bicbncoi.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2uebafmzm.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2gcqogryo.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2unwhoqxj.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myolkuld.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2gszqyfoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciexcsbw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2rvbskmnt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2pipwgnzc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2yxhesiaw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2quitxzxq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2wkrknzhe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2bpfnaqei.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2sbkqfudi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwirwgux.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gt2igpxvguk.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2mowmtgxq.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2xdsaaizf.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsbbqolq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2wtwrbrad.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2kjbxcxui.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2zwhcetam.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzzrhiwk.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hswnjolo.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wngfpqum.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2sarsqgvo.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2rfjetfca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2kdsexkrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2dlrcsdvn.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gt2ytsdqmjo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2zehrmwre.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2ziiusucg.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2alvqecim.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2smumbbqx.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2cmekrthh.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2djunorzq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gt2djbkblyp.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2itxmhtnn.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2iyzjtrcu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gt2kbfaaprc.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2pxtawstt.html


<!-- 参考信息 -->