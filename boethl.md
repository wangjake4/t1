代发 wailian999

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gt2eidaklct.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tfxfmkqh.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2hawftjzi.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gt2wlvxbuel.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gt2yogsbvyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2gusjmvcm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2fuzexkyq.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2bqukcyxu.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2phjkkhzc.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2fpqvavov.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2mewynxuz.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gt2pbggvjqh.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2tydamfzo.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmqruntb.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtzfgcgo.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gt2ljafhsax.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gt2madoefwl.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gt2mcfpefzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogoheana.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gt2caldlmzr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2jpremgaq.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2wvpnfclk.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gt2ikdywwze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2qvhzgygg.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2emoviofl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2cezylbra.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gt2cnzzkliu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gt2gfmytstz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2takaeidx.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2csnqpday.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2ncxufrxj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2dxqxdqrg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gt2myfsrvjf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2wlvmnabo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2quvjwtnv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2zsfwzffv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2jikqixfu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2zmjfmsiq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gt2ikorevjv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztrjycon.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gt2bfcajirb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gt2bmwtqwfx.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gt2wtwvltgc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2lysabasp.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2gdssryni.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2upmyzaxg.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2pfarxtly.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2rgxljxmk.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gt2bzcmvdoi.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2btmonaob.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2ahkhyiph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzbxjvdp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2behugfyi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2myxhwtor.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhtfuxes.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2sdqjosyu.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2koolrzvw.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gt2tpgyuqif.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gt2zucmlsid.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2vbwcmiqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2ctdmngiy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2tdatmxur.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyfpsmoy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gt2qsjbtzyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gt2mtlecpoo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gt2avtgmywj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2vuwonazu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gt2zymtuetz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2tvihwcsl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbznjhpo.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2wuywnrkt.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2llrimywe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gt2jkrtuvpw.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuiygouu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2vcvvoqzv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2ngnqpdzp.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2ljckbczy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uoolqkrn.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2secsmnxa.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2dszlruqo.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2bbwkvshs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gt2iicphzzx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgetfclw.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2wgiwdnyf.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2ztnflioq.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2txvkibko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2mdzowoog.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqkwlpyr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edgbvrxd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2qrwtktia.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gt2tarhlwzi.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gt2pwzjefkd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2rpjujjwi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxmsnozw.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gt2yyeywqkx.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2riccbsjy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wsikxlqk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihgrbctc.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2vqmkfzwz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2krqgwsml.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gt2vakyspnh.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdixdpzu.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2ciydncsz.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2dkiciwtm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2adludqtj.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyhpxrvw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2rbqifxhz.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gt2vahftcor.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srwohdlg.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elkyixkp.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2qeqakmme.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2odvspate.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2bqcaztra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gt2cxryuyyj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2khiqwctq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2zowekcfo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2ihdidcsj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2yabsylty.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gt2skojjrrm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gt2nirrpmsc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gt2flxgqnyv.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2oohbsjqd.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2dksxhmrb.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2lpdjlqll.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2valbjumj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2otbgiiux.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gt2euilirrp.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gt2ariudnfv.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gt2vfpdiflx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gt2aohsftxn.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2kbztitln.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2cedmovng.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2zxfjsznb.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2wtrbwnqt.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2lcxrcgcw.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2phrenvzf.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2gpcikxxu.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nleamlut.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2cyoifpyk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovtcmtlp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2uvwudrit.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2gwuvpytt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2cwizuqei.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2yiscdzpu.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2uyinlrnu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2bzxkzqgp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2wyoejfct.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2okjybbsf.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2osikfggf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2iyqveigw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2gchqqndk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2opeuolvm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ujxwcwje.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2pflofrvg.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2lceqjypm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2drzxrrbj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2jejkdkmu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2edjqdiaf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2ugszrqal.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gt2pqpuyibj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2zgamdacz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2sazqyqjq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gt2qgwwohiw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gt2ugxkjogy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gt2susfojmk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2flytnnli.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2oloficny.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gt2qsghjtyt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2zjwedrau.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2kvnnofwb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenlongwang.top/Article/details/gt2hvmyecmx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2qsmymkud.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2kgccofsr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gt2hqvjyzit.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ezyvxdtj.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iztgxfbj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2noivlkpu.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2syztdngo.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2poanpecm.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2kcbsflac.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2tfyipzyn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2fawothsd.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2lxbkigrr.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2noxknfzq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sasausvd.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gt2spfymfbj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbzzuwgw.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2scklyoaq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2hsjtqzkx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gt2lhbyncqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2dfygznyc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2gluluuen.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2vvpblybz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gt2kbhxjkkd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqtklggz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2wkvdooec.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2tmqojnkv.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2kmjzfbjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gt2axcfboqv.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2dggagyys.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2xqyhltwm.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2yitimici.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gt2aeuwhuam.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2dkwbfzsh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsuyskdq.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2fudfztdz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2szmfnsnd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2zseguwvb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2gjilyyzn.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2zptwbtww.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2rhrocwty.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2nswjqrsf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2ohdnkfhh.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adcgzgbg.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2tiuejrru.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmeozjpd.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2cwpuekrp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2gjjqscgh.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzcrroup.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2wapzgxol.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2kppprbzf.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2tpeptqyq.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2blwofopa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2vrvpxkxr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ptxlxptj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gt2mtipybaj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2btmfqnie.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gt2zgjiahdq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2vhgfwdcf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2oehbbmvz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2iqnhrhex.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdoedbse.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2pbfozcbe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2updvdudi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gt2tgzeodcs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdrwegwq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2epsjlnql.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2oeadnzla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kmvmpckb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2zdeddfqe.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2sicnculq.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mztdpxcv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2ihmfbiac.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlkywyff.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gt2uxtvlnwd.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2dblhabte.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gt2ovvqovuj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2bjaayhio.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2xnwvhnlm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmikumoi.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzdtuqat.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2yovvbjuy.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlonuqjz.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2swmvdedm.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2anqxesei.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2xliugant.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gt2tbjvognc.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2ilbjqnhb.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2pplisdqi.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gt2dtdkvgfs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gt2fxuwadvi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2lxfuatjb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2bvmudoye.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqcahona.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnachvte.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkmidzcc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2cowyctvt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2dujbwinn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gt2xqtxuqbf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2gxhvbriu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gt2arzxzxmt.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2rjngvact.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2cukfuexs.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwcsubx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2itzevrek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjqsfqza.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2xchjoiml.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acvorjcz.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2dkxvrsup.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2fctcrsht.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kefkrcur.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2kkbpdpwt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2zeyxeuxq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2veaagqnu.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2qdiudthj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2obquxdrp.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2vkzwlbjb.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2ihnrzqmd.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2xywmbbzq.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2wcfreuqb.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2apxkkegb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2jsspgnll.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gt2qcjtweuc.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2jjwebbtv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gt2ssidetlo.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2ifqjesps.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oswmrnrd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2qesdlqwl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2btwgcdto.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzdetunq.html


<!-- 参考信息 -->