代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttzthlaa.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2rdmqxich.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2bekccaox.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2aijnkgpp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2tifpycsw.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2plshatpv.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2nqnfmzpu.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gt2vjnjhxpz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gt2buxguedq.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gt2ftuetcyv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2juojjeyw.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2zkehhwpy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lbyjaiop.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2vririscf.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2eprzmcae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2itihleiz.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2oidjpmua.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gt2ztbhdfyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2oovliakg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gt2pkybrhcp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2jqprloxl.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2oilsumng.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2mgsnzgde.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2zkcfqcqp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gt2yykkrihz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2idtfmyhd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2pilgldwj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2angjxpgf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gt2vplzveln.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gt2xesgheog.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2rdxqtaoa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2nzgkkaxi.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2przemfpf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2vwagqvse.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2kqndtjuc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gt2qhjzurab.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gt2ladinihi.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gt2niicqatc.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ffojepwk.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2johfdxbi.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2iipxcyzi.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2yegwelof.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2vkwdgmmp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2rvswozhg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2vfjrexjk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2pmertaet.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2vcvnxcsg.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncskniym.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2vziojimm.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahisrkbh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzmeatjb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2nwkafmaq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2gkvffcgg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2vkgoeetv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2swqvmvxs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2puydmqoj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2ocuospxb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2xnwgifqo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2uygurtds.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gt2nbbkgsjp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2vkkzpnzx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2hbwbndkv.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2xijkbytx.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2owbwglky.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gt2riaqbbxm.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2riqjogdk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2mjpvjkyk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2ufqwynju.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2brljqlmw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2cwkfhgvb.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfotrglk.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2iarwbkmn.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2nhpigbtv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2wvoascgj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2gnsosdpl.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yibpnxqp.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2kchoeirs.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gt2lafgfybi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2xsqbkumh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2gzhdaoeu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrxzgkiz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2uvqaizzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gt2fgdelbcj.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gt2blppexuk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2rgksaocm.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2dspnougy.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2twljwuff.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2euanbhrj.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gt2hijsxjhy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2ksrzadls.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2tznkynxu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2gmqdrkgz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2naosgsxs.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2csokapgl.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gt2dlsypqex.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwbdfnja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2nychgcyn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2wmtwswgp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2vebawjtd.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2omcdslyj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2twzuvnqo.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2czrzxgvg.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpgwnlcx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2nuwjshec.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2nzoftkmv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gt2htugvcao.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2xrmvfxxh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gt2swrseuce.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2rpbcfgtv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2ajfcqfiq.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gt2nvxcctqs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gt2ulbjxjxk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gt2xizgsqqz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrbagxlc.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2liiljqxf.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2lmnehlhl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2azvfsaxa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2ojxqzove.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gt2yosrrdjc.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjrjaatx.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntxvgqrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrtpubpg.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gt2fbdqfkhs.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2ihtuqxzb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eijwrple.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2rwjaozyr.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2iuslddwz.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jtnumbqi.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocrscros.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gt2sspyrnqi.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2qqqvobyz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gt2tfvmyvfo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2vqklptsh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2fyjgarcd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2jcypgfcx.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2zbscurlb.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2cmcxwvdx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjmtstoo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gt2lvacnukq.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvcmhoxs.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2anfkofrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2vkwzqfwp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgkzlcbq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2xidimduz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2zvpufgse.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2ttevxepi.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2xptxrbvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2pvryfhfz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gt2hucjbqfw.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gt2bljmemgy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2khctnkvy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2ikkyffqs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2csewpyrt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2ktqlpzis.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gt2zrtapaxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2rozwvuhd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfrrojdb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2hawdifky.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2lxlumhqc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2gcfpbovr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gt2gihngtkb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ezpsadcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gt2mkssvseg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqebbakf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gt2knbjfiji.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2xdszrgzc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2jslmxuit.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtvcnsdl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2rugejpcv.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2gowftlia.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2tzvshyyu.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2cflvpvgc.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2rlpuiwct.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxjfgjlt.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2yvpvzdwr.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2keiqveow.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2fgdgflbd.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gt2aonjqtkg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkcongqx.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcczjogz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2netnzxox.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beskerla.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2glihtstd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vucvcsqp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2myfhdwyw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrnverbs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2sdcqemnd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekfrdigz.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gt2poqqrscq.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdpuzmpp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2myjsrmvu.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2peuokpov.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2gfrxxslm.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2kslspjer.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2dmjylnrh.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2wptuhrmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2dgmltjha.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2rvitdert.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2yukdoiqr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2nrxztguv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2nmqvpobo.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2lwxwazcv.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2noqmfreq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2szzpaijg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2ofzxsdxh.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2drngrxci.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2idjfjepb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2yscwvksc.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gt2dpgswadz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2hfgefnjp.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2xkbnmpih.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2dcosjuyq.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gt2udsahldn.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2dwszjjiu.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2zfucfmav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2irptkloq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2tovniydv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gt2tgorzyzh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2pmzwvooz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2dhtcrxfc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2qrrvhkdo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2iqvjovlx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2zcmlddbz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2obontlcs.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2bvmrrdjq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2mixgumwr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gt2ftoxmjcz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2goqsvjtj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2tkaegigi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2xyytftza.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2onxlkpzg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2zpsxipco.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2wxqjzkgs.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gt2sffeecsa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gt2fvthrorj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2jvoxmnok.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gt2pdlrjrix.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gt2zkyqswvq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2iaqkzwfg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gt2nhnhpazg.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gt2ewdvhnug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gt2gwovhheb.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2haadeiue.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gt2xvxrxikb.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gt2rpkfesdc.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2bqgqbvne.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2mdnqqnph.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2xbizlnkq.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gt2mwjfmiil.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2tfoggsrz.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2kjjwnheg.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gt2hpcyrciz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gt2lwobjcrk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gt2jsxwsuii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2bibpovpo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2ebymerey.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2kycywwbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2hsyhpnyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2torfglkn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2ogbienxw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2lcmmeqqw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2zffyzruh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gt2kyfidvrq.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2ykrszxtp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdgpbiq.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2tfyvtrzy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2fqsbbmsx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2oktjpgqe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gt2bgqqvijp.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2bhdbopma.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2ngaqeave.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2unijobys.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2kjmzygax.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2oqtesslu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2lmdpunbv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gt2kwjbmnss.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2qprdmtbg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubhkmusb.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2wumfcxno.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2xwgftrnv.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2zerbeojt.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2spulktqs.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2xlklruri.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gt2qfwbrdqd.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2twiyslwn.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2dsqofhma.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbwmahkq.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2icdsmpcn.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gt2iliafovt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gt2zszunboy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvtlpgxi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2wivoqtqh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gt2zuoadtgy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2arzgvvuc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2tlethpxs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2vhlmllzq.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gt2asndhkie.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2pprsqoxe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gt2eterquxm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2ismldxhg.html


<!-- 参考信息 -->