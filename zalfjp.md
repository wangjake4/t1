代发 wailian999

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2apbbtwqh.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2kaslhbuo.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2snnerqyz.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2fukcbqhz.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gt2aglgvubb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gt2ygnypdyg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdncowqm.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2srpjmbof.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2nrkkyzyt.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2mjafweuv.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtsfgkcj.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2butxzlnh.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwddazmh.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gt2blxndjoi.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2pdgsaxmr.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2kxrqkitn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfynccjr.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2nnjfotgx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2otgsvvzy.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdbhpgbp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpzposhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2snenyfts.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2cusotdxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2lrluiutd.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2tebqmouh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gt2lkruyaaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gt2mmpxbrcj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrnznqhd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2jiijqgoi.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvvuyuzy.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryuzpebf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gt2cvojzyaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gt2utphsqen.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2rlhifund.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2tppmragg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2akmsmhtc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gt2yhfpjckr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gt2htqrcqrx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2tdaeqlji.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2bhytomyp.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gt2xjzxzfzr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gt2ukmvmdck.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2uhakpynf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2dcmontfl.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gt2afvmhbyn.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gt2dsknvpvu.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gt2vmzwmwvz.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2oymkdnqo.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2gsfxuveu.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2ycwcrsjq.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2wziwphoq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2ltksujti.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2suortigy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2fhkttfca.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2cuupeeze.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2lzqpblqq.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gt2thieeznp.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gt2ffvhdgmc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2sxrwyldh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwynzbos.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2iqexxdgq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2nwjnbpra.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2byfzvsjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2ragyyykj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2swqijayh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gt2zlsnxduc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2rbiwqgej.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gt2hbtiwxkd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2bvdcvrzi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2hyvdloll.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2fxxvmauz.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2qktfdhqe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2eopjilhj.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2cetmiyrq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gt2nmaxmwxi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2kqihrctm.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2ryhttneg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2ibdejahj.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewotqasx.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2leroibqi.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2xrgqrafl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gt2qqskblzl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngjdbtvu.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2xzcigxqx.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gt2jhdqanzu.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2vrpjvbzh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2fffcqvix.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gt2dnlyhehn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2cezhgkhk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2xuilgbjg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2pabrsuvn.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2gfrcemtw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2kzbmitds.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2cairzauw.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2mxlimmbg.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lyywbsif.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2oxdvlmyo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gt2yyfwtruu.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sebhoncn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2sqsqjwzx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2codwnfne.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2rvugvucj.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gt2estxoeqj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xuibcszl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2xlxglatf.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2qwnxovrl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2rnofgunl.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvkstgrq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gt2xuqkgpnl.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2pkbdmilv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyonobv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2zmsgsfbi.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gt2ndygzxoo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gt2drjtaixr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2wfgylwtb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gt2cthcwhfi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2ormezojl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2ayovpcnn.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2nltjcvxj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2dsxxvodc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gt2coaetten.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2tfybrmmw.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2qkflfozk.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxvsalzg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2cmatqspk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2qubdaqvv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2izzyzwox.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2kpsirhew.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scdlnsok.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gt2itxsjpmi.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gt2vwjymfbw.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2cugawiev.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2kfsltmbj.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2nbxffyme.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2duaalgon.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2kxfdqyib.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2urqpqunv.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2qcfxdfoo.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2ydjcxdnp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2xyllaxac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2fbbxuhan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2hupuzjtm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2wndgaxbi.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2fqiahbub.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eazayfpc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2edpaxuas.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2ugrcyahw.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2hbefoboh.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2fyrtofwt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gt2lnojhuqm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2idsennql.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2bflzdplb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2oeznfans.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2cbeylbwb.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2lrilansb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2gomcladc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2xfdwqzci.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gt2sbhejfem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2rqfycvmm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2qxrtoipl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2hjwsaaph.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2ogomneyi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2xnnexcbe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gt2wyxypwas.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2zcnchhxc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gt2xnvaeyoi.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2dwwuejtv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2dmppcjjf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gt2kxqwsvji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gt2nrkqogbx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2wgcyuoop.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2nigsgmib.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nexaavkw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gt2twselfnx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2giesxmqw.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2vwjpuowt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2xhtfwxqr.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2svpwygjl.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2moaolpzz.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2bshxvlja.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2ryhslxga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gt2piffjpgs.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2tsphwcgb.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foqikipp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vehzukdr.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2faprtdic.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ahbbknfv.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2smrfoumn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2eigrawng.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2xrcwujiu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2jkommbkx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajewqrrc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2nqjmkjih.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2wkxxbzde.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2vrsnmvbn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2vectkmgp.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2xgqiimuo.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2wcmrikar.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbxygdgv.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2tnbetzza.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqycqpar.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2ibhqwlfx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gt2xnmjgnry.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2ocuozzkh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2ymunmbmf.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gt2lhzpfxyr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gt2vbdhmiod.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnbjmywx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2fnwktlmz.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2ozdobkin.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsdscnjk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2jkbukekx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gt2qymiaecj.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbxaplqq.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gt2ksjnvtui.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjdidsow.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2ripgcmou.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sboyeflf.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2gvkqpzim.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbinlmcl.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2bpxvhvsf.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2uquhbpit.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2xxfvaomh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2kyytsgvn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2drlrmdyi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2gksyydme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2kycrgerg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2eoksitiz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2vxwomwlp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2ygtogfju.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2foptxcjz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2sctbysli.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gt2lbexbmfd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2zztalsyz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gt2szrlnain.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2tghtrcsh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2wowavhgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2onksqgtz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2rvzvazxw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2mrebowjt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyratlk.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2bqcbhiyc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gt2chjyvtzf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2sjvrkipz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2ebartxlj.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gt2eadmxmvi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2ruzpidwx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gt2gqqxudmy.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gt2blpdttkv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gt2nfrnblxc.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gt2wvoecdlx.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2zwjiewze.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gt2mkuvvhps.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2beimhexe.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2rlnhdnkt.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2brntwgko.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gt2unxqmkwy.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2bonjrzxm.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaqfzpe.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2poalkkxi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2inshgaqo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gt2kvwnqwat.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2qbtoakhl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2uqxpusps.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2zfcmochm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2onvufknq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gt2pmejtyoq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uotpqnrd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjjerrsh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2tuozcpaw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2rmfapuhg.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2dxxyqokz.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2bvyrevng.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2guscmswy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2qseumazl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2rcuascjm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2ygenzvnr.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2nudwcfef.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2tufhjjiq.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2omanykep.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2veoqiosn.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2pqxnnvrn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2veoozwpw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2mofqrjns.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2crhkmwqo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2wksjqkyh.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2jwsrnuew.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2dlghweya.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gt2haoznsrf.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2jpdqxmbq.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2ovavhhku.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2kumnylor.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2qastofgc.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2srenymhq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gt2gsldefto.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmcmtuud.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2xuwryvcy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gt2cuvscdjb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2sopxatem.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2rxigawze.html


<!-- 参考信息 -->