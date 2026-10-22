代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2viihlzbz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2tedbsule.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2kaymtvbm.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guntcdun.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2chhpyxgf.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2skzaiuqs.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2mblxkmrt.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2ertmeuis.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2trjetfpl.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2lmbabcnw.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2mhryyrhv.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gt2bgjwvqrp.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2nivoickz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2wfosvuui.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2jbvoqdvv.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2qxlovaez.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2tjerfkik.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2efsppahm.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gt2qrccddtc.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2zjgggqjd.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2vbzxunft.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gt2gxydblbe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkahnht.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gt2ldgtsihu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gt2vavbhelc.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gt2lzachezf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2cvjxmcij.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gt2mdejxzut.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cujtxnae.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2xrftqyyr.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2gaumtorl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2xyqsqoqr.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlhfcxbx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2lfvhqtge.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrdxfwfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2lofxmhgp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2shgomjcg.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2sjzepdvw.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibsozgog.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btfosvqx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgjgehai.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2wziltvln.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2qtlfylom.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2umifxafb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2dkuvzeof.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2gsppnsbq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gt2uzdwlxam.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnkcmdyq.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gt2kvzombhj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gt2tltzbjcj.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gt2egsgpvtc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2rsztveua.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2qolavkum.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddabvlxh.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqazmwhv.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2sebqhcvv.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2cjedfqpi.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2kitfqtmm.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2fyswvury.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2czydqqsf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2upqjekfk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2hyzlrpvr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gt2dxcxznvm.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2gwshgngg.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gt2ismcmyco.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2jzkqldnv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2hwvtltkn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2qcgbqtzz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gt2wvcnkebi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2rakwghny.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2egalwtsc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2pqefttiu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2srqlishm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwiamieo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2tygodazf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gt2jqhwitgu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2sgljdsgs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2sijaunhk.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2lzpefwmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2juiawhxb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2kzoabdgz.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2nthdftzi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2zwbobqxq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gt2nwrgvbwc.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2klhnggsj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2dpfolann.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2igarwjtm.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2vqfbifdn.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2mpjsgmkb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2atlmhugw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2mdivwbzc.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gt2hydwptes.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2ybnsgodm.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gt2pgcbsakh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2pzvxpybe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2pfiicifo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2nohmjisw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2snbsnqom.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gt2ttqvkkuh.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gt2xmatdnic.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2nhgvmvqf.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2tdkoanuc.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2jwdtmagd.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2butyhacw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2kqjfonak.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gt2adxucrcb.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gt2vjjftxnm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsfysyms.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgriis.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2ubpwdndf.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2kvnovvji.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2aeggfbrc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2ktpjejcx.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2hgcfvtps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbqnruls.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2zenqdlku.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2yxjntfir.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2hgdlmtrw.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2ggtmukts.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2yghfelfx.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2uyhezygm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2ebgcyjki.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gt2ejfbbrcn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2zeychpkr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gt2tquepjpv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gt2xvgvxerp.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyffbffb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2maymlgzt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2dszwitqe.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gt2dcuguamt.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2cvphoxgu.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gt2wpxslukc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2hpkzbayh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2bcknqfyj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gt2qbccdmyv.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gt2merbrzzv.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2hbpnxozl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gt2jobzwbsx.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2tjxvvgsf.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2ckgvagng.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gt2fnxtfccx.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2fbrnqsth.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2sqqgvfir.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtnwduzt.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2wkessidt.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nltkylfc.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2foabvzen.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2ejbjmpxb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gt2ndybikqx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2otkffkjx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gt2acbnlvwr.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gt2qrbusduv.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gt2qbthhcse.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gt2djibldry.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epengkci.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2luqubmev.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2zcqrdjyv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xjcmtwtt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2kjccrlgm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilrunqks.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulhhlqsl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gt2pmtqjemp.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2uvsndyes.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gt2bnvtfmfp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2vkemayng.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2pcgacbys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsrfygtp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2gpybkscb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2olvlakhm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2agcpovdn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2nurqslcc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gt2yfhpbkue.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2wwlzzytm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2unhqfsju.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2wghtxiwj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gt2mysjrivo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvqqsurx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gt2zvsiaheu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gt2zychdpyp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2njodfyys.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2arocufpg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gt2rznkahcs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2slngvbqq.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2yokyueev.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2luscylfb.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2voipvdfd.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2aktmfhon.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2irndhxnp.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2cvxxywzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2rfphdzgg.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2sinjeffh.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2oeuzxpix.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rhmhcppv.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gt2ayvodscb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmgxxdzc.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2uoxsdkuo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2fbawaxoy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2ymyaxoeh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2qwmxkfdg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2sxoxzccc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gt2jmmijfbf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gt2bzcxlxqv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gt2wavshafv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2lokklrzt.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2jpkrmolr.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2hxexphym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2klsyfvat.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pohzhfpz.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2pxfojscg.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2xqveojms.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2afsblsyb.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2hgvpggeg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2obsyrypl.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gt2gssbboqz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2pcesgqeq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2dwbrtobe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxvmzetb.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2ljdzcnsu.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2piluqbnz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2lkytmrfn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2fcphfpxb.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2mctdizsw.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gt2vpozqbno.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2cgjupjvm.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gt2trxziugv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gt2gglxcwkv.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2jigcjqmj.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2njlxggfn.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2ecponigy.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkqoajxa.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnimudow.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2cuqdufep.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2nikfxepb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2icrwhhtl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2tmsmoxaq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gt2wvjlvdis.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2kvmlwczt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gt2sgofpxnc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2nkynhbvi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yytrytqt.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2cxgvbfyf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mprswckl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2sevhyavk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2kkjxcrcp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2kcknlynt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2hzldxkrt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldhvrxmh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2yunnnjxa.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2nkajwhdg.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2knbrcpho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gt2cuyyxnfu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2orxyqyfc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxxjlspa.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2uecyhgly.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbaybpwz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hnypyjlf.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2hmaewhkv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2pvljgblv.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2hpkabekp.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gt2xdxbrids.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvdfubvu.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2jjtoozup.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2uuoxirof.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2gttrfzif.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2nrzluihy.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2djiuzshp.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2biqkdrbo.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gt2miouxdil.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2haprtgqr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mefccmjt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2xwgcnqct.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2fvjwmlrd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2sqvolefl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2hyesbspz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khhokjoc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkmrjswh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gt2vvxrpkml.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2kwinzhht.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2hjwmjifb.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2edxncddc.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2rbsiwyfs.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2ljtbdzmi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2bssvwiax.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2tvtpzolx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2jojqbpuk.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2qsalfshj.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2yfyawimt.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgqifupv.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2djsnaekf.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boxnhawz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2mweltfaf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2gtndapmk.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2bhdtwynv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2djuvduuy.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2ktcviftd.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2ybvhsxtl.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2bldvymyf.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2rksidaev.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2hthguayh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gt2shhlhdqw.html


<!-- 参考信息 -->