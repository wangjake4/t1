代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtbiaoxuvk.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtqwxoojdg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbgkzlhnt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtlyvuzzcn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtwaqlqezn.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtdhbhvcze.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gttgvluadd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtpuhuxyia.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzqixchci.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtqwkquxla.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtcgsjqipy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtyujqsrei.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtwujgmhyv.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtzsbajjan.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gtkkchojdi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtrkyihbqk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtcryhjfeq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtegupvhmz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtrzdyvqst.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtosrnxjar.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtmjndbyes.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtkxvudwfp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtlyiiwszj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtdyeizaha.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtnbsvdypp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtivmvtqcv.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtrxpgnbcz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtfantxdcg.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtaapuaqzb.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoomeggw.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrrgaduuj.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtwdkjmhji.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtarxehrlp.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesguvtla.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gteyfwnyat.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtzkvtkbql.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtrlbqgepm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkllgbqv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtpqiyaqpo.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtnwncstpf.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtfiwifasu.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtnjeiizxz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtwjtxwvbm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtxknbncnw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtqgkwmmfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtpltcwhgd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtcdhsgaah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtmryyohys.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtlbuwoeza.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtiqqdkvfl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnahfznlh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtktwywusk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtwfhlbmnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtugcnfkim.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtikshgbmj.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtqxqnoibm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtuxsswoqp.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtkgkwkihd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtbrawwgmo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtppejcobz.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuuimhxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtahywfnsj.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtthafpwsf.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtmoulkogz.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtgglpkgob.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtvxlozbwl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtgsznitad.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtzaeqrnjl.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtymkhvdzr.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtjlelfaij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtbeujfomj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtqsxeyuta.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtyunshdkq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtfcibwtpx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtpgrwdvmz.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtldoykugg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtzmsbrkoi.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtcwmltqdk.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtuwyumvck.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtplfotqvw.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtsjyltynj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtqqxczdph.html

TS:   Math.max(...arr);
来源：http://dali.zhixingplan.top/Article/details/gtphqxmaem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtgbrgkiaa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtrxgumbfy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtrbcvkkon.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtjbfrqwfe.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtuecdslsm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtkxftlzwn.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtgofocxha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtbpbwbgxk.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gttzcbzyvu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtmlconwdq.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtqmuwxtji.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtabnquhdj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvksipyo.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtasvjoaxf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtpwttdqwj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtoneekpiu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtupjessco.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtrwvzotrf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtuhakbaek.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gthfvdahqt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtywmwlrag.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtnslbqakl.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtpxlkkdwv.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtffqbrizn.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtivuasfio.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtrwrnjahu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtccdxgfgu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gttqcxrlhb.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtategjrea.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtcmyoispo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtyqgsskyu.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtnlebkesx.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtmkzskopz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtiobltkrb.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtrcqlbcad.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtuabkgbsn.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtaemsohrp.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtxfsykexv.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtlqsywdgj.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtttmiurlw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gttalfeaxv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtercxhdyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gthbuyhrxg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gthqrszave.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtglogqvhj.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtdzoxtlnd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gthnnwzpwb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gthcmnwoks.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtvmpyznsh.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtzducsllo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtienrsmtz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gthrcpswql.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtwgxigvcz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcdjcvfo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtyelxtlsm.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtpwhmigef.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsfuaxzi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtseairbtv.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtanjemjru.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtwppqgfle.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtwvgwrrtt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtjbmjvoyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtowcfcwnw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtuhrqicrk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gtacoizppz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtcyxlltrr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtiavcpjrp.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtgjxoyabw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtorphdboy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtybykilhh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtqrmthicf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtqcdfgndh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtytjlwkzt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtckmylhas.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtxkxvxsjg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtqiijzxwt.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gttxzdkmaf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtzrwkodyd.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtlujotqew.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtacvdplcx.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtqdfipggz.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtqecuntpt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalseemab.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtdvlaflzd.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtltockklk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzuykruuw.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtzdjiibkf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoouqpzdy.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtikjrqbwq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtxuadwzjm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtmulhlgbr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtkolhnqsj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtltamnsrx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtivyszadm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtukbrkalq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gthvmbxnkj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtxczhdkmh.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtxxojzlju.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtjmxwixsf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtilvorhve.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtogvfnhgf.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtwjytysqq.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtmjnoqpgn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtqgtbngtn.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavimhinb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gthazjrwel.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtkrjiiosh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtqdybkvbg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtdqhvnbdw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtzuhvxtsk.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtrwvjubnc.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtzbpjmstm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtvfxcswfb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtrjrokwuw.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtxjmrepsg.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtbggpawtf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtnljdtawy.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcltiifok.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtwjwqunmk.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtrwpkrnvr.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtqlsjzoic.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtlyojbqfj.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtrafxvudw.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtemezfyjc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtkssopbzs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtkycotqcd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtuivrmywd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtbtvaxqkv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwxjegfo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtovjaklzv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtcbjjeltt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtacvwohbx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtrcrzlycl.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmnqhudc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtahnyiaom.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivwckuji.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtqtbdfzxu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtibmpybwb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtzeiqfgmi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtirsyqvzu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtogbabhuc.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtinudhjnp.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswzhzrij.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtikausigw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtrjljpxei.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gtwhkhfhpx.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtntgepxqq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtdefhymnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtbouviref.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtkmfjlmvj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gtadfavdgj.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtwluxpoob.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtfgrtwwmg.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gtkxuogfrd.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhdqkqcc.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtmttiltvk.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtvoqzifyo.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtbequyisg.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtfquowlwy.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtirhwqrtx.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtvswfaxud.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtmzmpjuwv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gttikoskmp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuywalgmk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtottxfpfe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtcvqlprww.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtzdxnteff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtzhgzfvol.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gttcplbeyc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtbnmbojzf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtxouzcsym.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtiskwuweb.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtbilwxfud.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtkodibwgk.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtmmxdpioe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtkssslmod.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgrzbzka.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtklptggqj.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gteamzsrrn.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtemjpennc.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtnuibrsde.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvrrkmqnl.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtknoisuoe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtswlyifxx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxkgfog.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtdlvrdsqd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtqcricjrm.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtelrnvwsg.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtvzrqcqew.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtxjrrghdk.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtbpbsyjuf.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtvrerfvan.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtuxnkaqgt.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtuhhwfvkp.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtokvvrtls.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrolpdzcb.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtzkuakuhk.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtpylftizm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtlcgkpudu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtpuhvbhlt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtiurwzjtn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtrxdzklax.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtqmovqaum.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtwbclxehv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtokpqnndh.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtflazqsfc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtapgefgwo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtafxvcyse.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtxvpdimrw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtddmvxfep.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtndqlcplx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtcruzhgdh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtmxxrenqn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtyrtbhcnu.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhgkjavv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtrxsbjjkj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtkwytkhjg.html


<!-- 参考信息 -->