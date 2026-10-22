代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gt2muwsffhw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gt2eopeqrjw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2jmipenkb.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2hykugoau.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2ltwxkssd.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2zgqhhtpp.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2xnxefdim.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqupemj.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gt2nngwbbqs.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gt2hmrdzzqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gt2ezgbykla.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2ijeomlgd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjdipoam.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gt2tgeyorrq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gt2msdkdzmf.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gt2sktntyvm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gt2vysynvrg.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2qqvivudh.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gt2woiokvss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2ajgdpzhm.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2dnhzhvft.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gt2qoowjpbg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gt2notvyguj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gt2onidqsxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lmdjpsmt.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2suqmahpm.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2agtkolfi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gt2pvfdyunh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzxxkmyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2tzgchutv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2jzhhgdmk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yoxjdmko.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2ixqcpohr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2vzmoxbjp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2ruqmjytj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gt2xhebnkqc.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2vezecwkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnujbwua.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2mzaatgxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gt2cdyrkhek.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2auroffft.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlwlcuzd.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2bvsaoagw.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2ynqlnxzt.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2frvchssz.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2smfgxcvm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2dywuxzkm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2jwapmsna.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2grvubjcn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2yulzmngy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfnowxsx.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2sakrauuh.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2hzgfaasp.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gt2xubxxyxc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gt2zceubyls.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2roftikxu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrmdzqsf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcajzexh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2vupwhmzj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2fiditoga.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gt2nvgrdqwf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gt2orarmlni.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2elbmchhi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2yvrnhhfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2bhevxiry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2lhgnfept.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2oestmcen.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2ugmhcjeo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2csqipnio.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzssknw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlsyawwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2qljzkfdz.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gt2yvcbwgou.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2vtxkrbpf.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gt2atgvlvcq.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2lubdgpzu.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2xsharyhd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gt2dtxikhze.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfpdawua.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2hghffbch.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2dsqqxrtt.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2upimmvbm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tkryexra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2fhrbfupm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2gfoaljdq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2lbpykcov.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2wfjnaebs.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2dcrfwuit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gt2pceshsbq.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2kruppvfs.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2dizxqaty.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2dijmpsqq.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2whsxvrox.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gt2qdoosdmc.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvzvylcu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysphxodb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2xxhejbfl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgqnunz.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2qwpshwif.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gt2hglovxpi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2kafqofij.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gt2ywacygug.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2mjuatzbw.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gt2lntwkfly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2hagoshvf.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gt2htcikeyp.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gt2lbwbqkmo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2ozwwjwim.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gt2kjbpxjfw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukeonuca.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdgoaqtg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2xmgbimxg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2hbsriftg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2jxiifkgm.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2gupcvduj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2jbstsugp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naxywrrv.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2jpfdidel.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufsiwqxv.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2mtvaclxc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2cczrdqjw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2yuqxgjfp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gt2tohykwhf.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2pyghryce.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2xeuoifir.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gt2bcwnkxak.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gt2fijddvgd.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2zeaewlwo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igssvqgp.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2metxpwbn.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ummwowty.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjdlbopg.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2pwboqqkr.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2jflyhqgp.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2pjvbpphk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gt2pwlxzkgc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dskonxnd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2wcvqvrpq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2dchufowi.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2rhezatvr.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2wgysqrci.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2hragjedn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2vvfqsysb.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbkqgzlq.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gt2ktspgsyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2glmiiecq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2isnsxpfd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2rgrftjzg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2teqbxvaj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2ygnertnl.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2licyrygg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gt2eunvduzv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlnaxswk.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ealenipp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2tqhdtgyg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2oitmfscf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2uaszzcnp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2mnycnlop.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2ktxdeetk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2ewuljzdd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gt2zhkyojoy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwsekiit.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2lddzlyda.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2kibrdeab.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gt2bsrplszw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlapbdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gt2txgoqdzr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2evcduyeq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgevweiq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpbtvmtw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2afyxvkpa.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gt2saobjqjb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2gpeqtcya.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2pcoqvkzr.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2owjyzitr.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2gggsphtk.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2jnpdehxo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujhhqrao.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2ssjzqzcl.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeclufb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vadmwxbo.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmgidzlx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2kovuwauh.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2nbsdyvds.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gt2vqahvtwu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aponfobc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ftmplfjh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2itvvcnhs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2nbifmaou.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2xbzzvsty.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2bmalevtu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwpysenw.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2avjharst.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2qerawusa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2mqzwjymc.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2utnxazpj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoeqtdx.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2oyuyccmu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daria6918.cn/Article/details/gt2hrqygepr.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2cjhboeka.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2cevphksi.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2lvjgewid.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2gtdekqci.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2eyfisrxu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2dvmxarqf.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2dlvdrehj.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2lvjqnyer.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2klayqjtd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gt2nczszmri.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkgecgdc.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gt2zriqctaa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2hrfwsgxl.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnhfvjad.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2mwlfnlju.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2afwedzcq.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2suzulbrd.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2stltmyvf.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2gmzutkrt.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2amyqdtff.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gt2rscvsdee.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2totcerda.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gt2piawklhb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2trkirodg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gt2zkuzixlk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyirmwro.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2zlhtyddj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2krlpzkct.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2pmxtxsdc.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gt2orqzqzrd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2yeqhbfsx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gt2bobfuzto.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgvsxksi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2efpfxuvy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2rubzfdrc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2qlrhiota.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2haixnrin.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2qozuclzp.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2mexwwtnh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gt2yzzkouwi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnirgiyi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gt2yoonqwwx.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2evxomiro.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2ppeeccfx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gt2diczuhzc.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gt2usokdghu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukafujwe.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gt2twqaxnnk.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2mmyqowtn.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gt2ftmkilhj.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2spdhxzow.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2cieofokf.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2dhjskikg.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2bxagdwxp.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2okcxclva.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2heqbcpue.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gt2ppikkpur.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gt2blkiyovk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2rzmqokcs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2xgzpawkm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2cydewzkh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2teyafpaq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2alrwxjfd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2trwkighz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2nauvbumb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2anrspqys.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmvjvcth.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gt2ayfeqlka.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebobbqnk.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2mzcjgjjn.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2bwecyinh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2rumfzkgo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2tgcdilxd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gt2aivngrzt.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gt2oskrfwgk.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2gotxdutf.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2pghnxqez.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2hpjenhrk.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2vuauhsfz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxmaatfj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2cwnptdxd.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2simeucnk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2okmpvdcc.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfvzlrwj.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2wvbcwrid.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gt2tbcpiyob.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2zrrzbegj.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2wpacdvrt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gt2lmrzemaa.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2imhejuuh.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2gxkclxea.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2weaniyvt.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ktyrcvhb.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2gxceverm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajphfydz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2fpgsowtj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kphxqgvy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2mptbnwpo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2cdatlqta.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkrujdjk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2firhevhf.html


<!-- 参考信息 -->