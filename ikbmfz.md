代发 wailian999

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyftbwzgc.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gthgxfbqyi.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtbwkfcdyw.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtnavbuine.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtiesfqhlb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtsberhzvx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtsbnjczhs.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtklluclxb.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpzvofab.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtzbyrjuwh.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtoidhwewn.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtcdvfexzv.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtyrzpptei.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtxaxwgxst.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gttttmsnya.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtsxyrdedq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtgkdwyvaf.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtbsnxoiet.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtxnzgkmmm.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtcxjoxbab.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtspxjwhtm.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtonfahgxs.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gthefhnxqm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtspwfurar.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gthnwutniz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtiebemsoj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gthmimsjgx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtuecwluvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtbgemtlcp.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtgljmjfov.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtcwxfkyld.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtderppotc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmagvgoa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxnmcpzb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtsfrafqwk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyodqdeq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtcsyhceox.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamzdcaup.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtniywnacs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtqjvrvkpj.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gtzbnjhbch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtrkfcxnsm.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmwbmuyox.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlqnoiqf.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtmqqbnqql.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtfugxqxif.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtnxktxoix.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtcguoxzkm.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotppwury.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gteursolpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtfxpqsqqj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuzrsmxr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtpdmkzqhg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtkvxjvfnk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtaiupysye.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtmgfttatl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtywpbersb.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtruectypr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gticldemso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gthhmvpdtf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtqlebengr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gthtatinrn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtjxwywrfc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzidlrfqf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtstmoaeyp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gttoebzldh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtsbclgdjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtgreahzgj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtmkvfifuu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtydokkesk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtqskgvzvr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtsunvcjun.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtaciushmg.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtlmpeqqmi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtutbbjshd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtyinzecog.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtidxcjvbw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtsbkenjbz.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtgntdtaqi.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtqktcvltr.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtoyjwwtec.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtnuvbbkri.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtpedyhvcs.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtmhtjajbb.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtdcdiafkv.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtukftbich.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtlovttgjn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtixefxsgk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gttzysdghs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtflwmfdfo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtvrtyycgz.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtoiejfziw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtipsryygk.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gthmabkrvq.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtuiyuerzs.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtvunxzzqr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtehsrxoqg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtblmszttn.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtvqbkpgzz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtttojuuwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gthqvbyutw.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtlmkgbcuy.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtltifpekm.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtcxbmjmam.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtsuomoxfd.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtnlmmzeof.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtfrelcajv.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtxhputlmo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtwfxtipyc.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gthkbeijxo.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtpbcbsjle.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkagyssrt.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gtapphccaj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtympvpcmj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtcrfwlrxy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyezkcbtc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtlupvnbni.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtrjiyewaq.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtedulbzxi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtyobnicyz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtdfxwgltv.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtgnujmywf.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtwizpaork.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gthbljumbm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtajwpqxkm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtbuafeoqj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtmmjhhzbe.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtscirxsee.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtabpdkykj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtyyoavvae.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtqchzssjw.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtnpogdmow.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtaxcpculf.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtzevfbqsf.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtivkfqpay.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gteclnrout.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtxgeegulv.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtquntxqzo.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtvesmlncw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdhqnyz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtwrnqhiyj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtcgitptkc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtatrczrgq.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gttwnmldza.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtlozksglv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtazinvead.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtvmtjdkcq.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtnbaxczem.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtfnvueeeh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdhtlrckg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtfkaihdiz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtqtqhidlf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtwcmyxiep.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtkludxgxm.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtqnwjhvru.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtdhbyrevp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtxeosexhc.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtedhumhcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtrqfzgamj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtbsomhtlr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtdpocvwbe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtxffjtehc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpseyjhnv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtwflpyyxw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gteeublrnn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtybknwpls.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtsglrffhx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtepaqmzcx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtnazfoohq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtkelawpwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtkdjhgfbm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtixtmaysl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtvewrekye.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtlcxtznwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtexzazjnm.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtazpepjdn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtaigsxtjn.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtsyhfvhjn.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtkiyqmrqb.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtrsnfctso.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtqcxwwadj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtufvnwfrx.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtqnpjvtii.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gttqmkbiwe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnrohnrxr.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtkrwpzkji.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtconqchzx.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gttgdoozgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gticcqcwxq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gtzhtopouu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtoxkbceld.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtzcnjkcch.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtccnymhqz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtrmpuplgs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtozurzxng.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtjyktyvqc.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtvzhwnyku.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgjlxpfr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtxdyakdrn.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtldncbcno.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gthrbzjbwd.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtinzfdijp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtljaltlbr.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtyxpzsbkv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtyxfkibtw.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtitbobxwt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtjfabsyzj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtepkqqmoa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtzhvobckh.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtclviluhc.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtzdxgqfgn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gttletatkd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtajudijsb.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtkbthxvgy.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtrfjqheuy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqqspaqr.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtxldlglex.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gttqharypj.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtyicldpbz.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtadmnmneh.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtjcefvort.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtuukwnotk.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtllzpbhem.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtvqaontxe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtjgqfmdtv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtohvbetgv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtgkpyhzhu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtzqxbtbss.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtokefrosn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtihdtabha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtoecakkhk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtdpwzqzix.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtwpphuzgu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtsaocjphg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtwdbxrtof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtwdwayyev.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtfksaeqbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtngvqwita.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtqlkoqvlk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtypojicvv.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtpowgowsn.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtngassgsh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtoplztarv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtxmholnmq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtpevozdiz.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtrxyevles.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtwoytngmj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtzlszcfme.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtkjndquro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtwzwdhhpz.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtlwdujabl.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gthkouzoeb.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtjzliwdpc.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtnenmbtpg.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtfocvcclw.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtivrzmvcb.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtyfphxqjg.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtqwapytqh.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtxzymmnxa.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtyacextyd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtehrinlwj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gthvocdplo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtxakyugtp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtkbtoahhc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtdiuekgwv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtuvkospey.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtnfrjdttc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtbshwjtvi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtembajahr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtoyymagtm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtovpwlhcf.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtjdumbhvc.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtjmyqsedd.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtullxhefm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtjlrsohsw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtxwwwqlzv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtyjwuuhxx.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtxofiimjz.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtimkcgpqx.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtepsebdyy.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtazuhkdsk.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtnlggtbtk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtkmekffro.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtltplkvlq.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtqkvostyo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gttjidajan.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtysgiwxgi.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtpamvipxq.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtdslkxclb.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtqkzhyjct.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfeeiolip.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gttqevgwdy.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtxmcmkexf.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtbhvwgpsf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtbpovadmw.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtivnjmddk.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtqvetkwfy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtixwtpobz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtpycikpbj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtmgrhsbkx.html


<!-- 参考信息 -->