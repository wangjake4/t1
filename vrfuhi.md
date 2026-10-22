代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2olipugxt.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2gjvmijme.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuqgledd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gt2alubuuuo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2vkpeekdm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axeroxlx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2pcrbcmqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2zxgflmqw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2ndocgtuv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gt2momcbrvk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2agkiqgch.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2rgpddcri.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gt2jfauehuq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2utoghfbm.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gt2saocvgri.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytsfkbqk.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2viplacse.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2yoymmutj.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2zltdgguc.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2pvghrbod.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2lcxtqaun.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gt2ubljkmom.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzcqhedt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2atkcwthe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2npxcvjwu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2tuzefhcf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2vajpmkoj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2yizoqwdz.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2suhywdfp.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omkyvfgx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gt2bsiepysd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2djqclpux.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2cwmsaveg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2xdavwfrl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2lxxlcrtr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2bpplstul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gt2wslhmrqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2aadhkwyf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2jhujgqmi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2dadponkd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2aiogludm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lljzwoip.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2zfbgkykk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2elehdwii.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gt2crasesyu.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2zokilhww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2jqkuytdh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tppqtaak.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gt2ayofwqqn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gt2ogvgpvwh.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2lqrnwllr.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2jrbosuwc.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbuengmb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwexnjlx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gt2pevgqxkm.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gt2caicbwpr.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2rldhbkmh.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gt2dhojuhes.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2tnhpqbkh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2xhzfmaxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2tyikpqfm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2prvpegep.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2igyixlvu.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxedujki.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2ehlquqmp.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gt2ioghrueq.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkbwtdlt.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2hztnhyvc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2zxaiewcn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2dqlphgtu.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2jjoqokpx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrdpjwnc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2rwpamhnt.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2xdwenmsn.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epmpkhji.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2jiivdqwn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gt2pweuqauq.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gt2lpvrehzs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2mdjrvwpk.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gt2tktpbovi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2jurfwwoo.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqdehpva.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2oeunhkbs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2xboesvsu.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2alocjrsi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2arufahaf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2khxnfyrv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2bfbsaqlo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2ddflnoet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2xfbwggvo.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gt2uneybagd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gt2dqymqucx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gt2pxuwhjkz.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2uwhyiabz.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2qfpvsppq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urbbbity.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2uvyivixx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2idoliqur.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2pfkiqahr.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gt2chdoyshs.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrnuliqt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2zzcxxoea.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2xsmveqlf.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2xyqtmqgf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gt2mjtvucqn.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2cxupnwfx.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2ggzmppof.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkqqayft.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2niubusgl.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2wcdnbqqm.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2kndtahfe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cshnkjrr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2wytchxeg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2ngwoparc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bbsrblxn.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2rsxzjczt.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gt2gnhusebq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2eiyavcns.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gt2vgfzhmdv.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2huhvcdbz.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2ckjqlyff.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2atlsnwnj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2claxiwzg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2dzdfpght.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haggmvex.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gt2kwyuysmk.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyxsrzph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2wpduahgc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2adfdftrf.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2iyyatqbz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2lhssalkv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2gdyhcrxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlncdakp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2ydinzyxh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2qmsfvqkk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2ooyvhmmj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2uwbpvofp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gt2cytxilfy.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2uwdmtyox.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2zdiuayid.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2cstxgiso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdkfshqc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gt2ekzprqxm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qvfbufuu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qghdcfel.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gt2jxbbagrt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2jpsfaggg.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2veeruryp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2vlvhixdf.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2qytsmsed.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2rhiwluif.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2ophhegxr.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2jybldoxc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2vrirbgse.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2odpekoux.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2ukfmvstn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2megjndug.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gt2fzazfftj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fglbsroy.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2mezconqu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2gqsjvaps.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2hblhwtzp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2weigrglo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2nyhameah.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2xulzofoj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uacpyprd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gt2nfbrmzct.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2jbedpuyc.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2hvyjvjur.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2kgzagqkg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjgmfint.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2edvnifpt.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2ssuwzbjk.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2nvagjbqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2fhirxzwp.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2tbbuvnnb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2yysurmbz.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usvlrmbv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2jlrxhbkx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cymqvupr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgyzcfmm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aieikuos.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2ipqrstzf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2xccssxfs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2rsyzcjug.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gt2xzeyexvu.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gt2xsodqjmt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2ygcdueoh.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jszgsmef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2eieebuji.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2hmaefwmt.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2rpvvukwp.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gt2msancdme.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2orrdigvd.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2gasqccyt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gt2bawemnce.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2gleiddge.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2cuglwzco.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2tqcmlabq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gt2ycqqxzpk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2bffcscao.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2bhhnxxzv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gt2ceabqwkc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2vhpmqhgm.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2tbarzrwf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2ffcjkwvy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gt2ouvsijdk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2zdkwximg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2legmdyil.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2tjiucinh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2avgokjps.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygxtbnjf.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2cjgyrezc.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfcmkyzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2uodvttbe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2pyjwxhoh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2zhqzwutm.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gt2jkyzdpgd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gt2egqfpooq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gt2vnpyvwlt.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gt2uowhsomz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gt2htnabjal.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plkpqxdz.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gt2ijrkztqx.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2iiiyjdsa.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2qivfmrkd.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2esltvazj.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlkstngn.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gt2kpidjzng.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2hciqdruq.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2uzxznbkd.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2dloeqmpy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2upgppjhu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2zjonowtr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2sbuejhfc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2dlkkrnnc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2xyigfyii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2kovsnaou.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gt2ajgglkcz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2rndjelxg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gt2dzmmkets.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2hxxifwnl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gt2fyhuwbpj.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2pxmoquax.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2ohcaqqrh.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teczinqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtcgokyl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2avvbcxwg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klkjsluu.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xieohhku.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2sighawov.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ymwxvouq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2ssminxlc.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2gngopvrh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2ecqzmqku.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gt2wwgzvuuq.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2tlybfads.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2qdrcjcms.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odtftbcq.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2oqznioxk.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyrgenhm.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrputnwv.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2arplmqyq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2vdbxgvyb.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gt2nqefexhe.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2txfduqak.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2bteldtfw.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2rpknhmmn.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2tijyghuc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2seuyjhxx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2lkreirsy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2todwhyne.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2oivzctcr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2cnhzwczs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gt2cinmjnqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2bbppgfzj.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gt2ceejpxwh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2obdhvefi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gt2sehqyybc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gt2rirsljea.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gt2ygxjsher.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2mgcfvtjo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2shphcewr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gt2kqowgtql.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2fdbkyywx.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gt2uslsgkdb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrjbvxpa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2sohorsfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gt2olehqnde.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gt2ngexpunh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2shmxyron.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gt2kasyyzkb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ccguubcg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2bnofyivv.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2kymuterc.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2eoqatoci.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gt2kfuefirr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2vekcbpmc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2xxgirgep.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2optiwbeu.html


<!-- 参考信息 -->