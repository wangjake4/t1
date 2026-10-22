代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpmroexp.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xeokyulg.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gt2vqfhajeu.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2dharzoqr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbwykswq.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gt2jurashdw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2ubnwgdvj.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2hwzvaiwl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2pkhgkkph.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2kgolwnlv.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2sexkield.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2cjrymkrz.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2reuqomhu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2bdelhfly.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gt2ytknqlfy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2gtjgjefl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2svyywmeg.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2ilrlbzzk.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2bbrjvoln.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gt2pyqhneal.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjtceygd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhxghrka.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2njqcovjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2zewzagbu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2aoqyzbfj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2jsihxtsn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gt2ptmvxuvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2hzzukeza.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2mdedtftu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfbrgskm.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bchcflyh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2khbexfuf.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2ujvyryew.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2tffgohsf.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2iwxrtjtp.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2guqjtgxi.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2gqaysonq.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2oddipwwe.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gt2wpvfyyxd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2evyhwrvr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzbqtqgw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkoqkhbc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rocwfxig.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2kmfrvawi.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2lxotgoro.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gt2znohaiuw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gt2olbjyhab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2bnngwdru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2bbsommuy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2yapergsg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2kvpwihqa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbpyjupt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2fqlszvjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2xjemboap.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2lwwyluhf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2hoouxbhr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2zpcoujih.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2lvhxwpkd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2ajndbgqd.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2ttwgztzm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2bgskrhrh.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2uwpdzfwj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekndhw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2chznthwm.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gt2mataptfw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2cbuebcwa.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2blfozems.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gt2mfezjrtr.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2vraxkbkb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2ircyjudg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2xumuhkvn.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2bfujtoat.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2oiwxquqr.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2bpvkazgy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2qrvvakhy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gt2vxqmqqec.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2rybfgfrd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2pevhaxsl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2mbojmhgo.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gt2vhwvwaox.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlidmy.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gt2ypnfhklm.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2veupnrdl.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2bsfazhtn.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gt2cjbqlsod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2oftehfgh.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2rkrzarnc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2zuipjxoj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2mhbwgjkw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyvmeowq.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaebthil.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2pmucmjqz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2mbfthhff.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gt2jhvyijma.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2jieumakv.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2acecucsq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2ygnfxuhr.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2ezpxogkn.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgfdhrbk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2wnlcouae.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2ipgelbyi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2gqeyfvsm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2jnjbntpi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2jjmvqirq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2guxtpacz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjozavqy.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2ylwfchbl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gt2deeorfml.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2qhabbnyn.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2uwnpcdaw.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2gcvwmvbf.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2uxssczlh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltxckuco.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2snaakvkn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2znitfrgi.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gt2nuiihbin.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2lbdatcfs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gt2pwrodpgp.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2aojhccbm.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqmhxtob.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2uuixswsa.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2uogquqpv.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2zvzmpfyt.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2lntqszvn.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2wtjpjkef.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gt2apxbmewy.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2ovjzdmrk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2gegbxzxr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2krachqbf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2upaggtuo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhmbujlk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2psyhsrof.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2tzhlhtrr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gt2lgfgeunr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gt2tcseyhvc.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2zwqajifl.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2egwkpafp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2zwuxricl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2upswzoyo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2dyosekom.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2tqbbkjun.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gt2wjbhpfnr.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2vxpfinwm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gt2hslfumnu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gt2driigfmu.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2zbupjnde.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2gqisigps.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2azllkrqy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2qcgzprnn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2zrtwwdji.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2qmhvckrx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gt2sbfaexyi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2khidvyyw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2xdwxvbko.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2mafypmnz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2psrmsrlt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2fvmpikth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2yghckopv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2sauawomg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2lvhcxehv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2axzbngqn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckkcklgj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxdjugal.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2vdaamewq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2oqbevzws.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvykqadz.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfvtfgdr.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2owmihjvd.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2crgirbci.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2onzxjboe.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2gplkhvjo.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gt2nrsceiye.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbsrklfh.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2wawmtfsu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xznxvcam.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxkiicyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gt2fnwfwqmw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2bekwbmdp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2qpkmesdx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucyrwtmd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gt2najwpccv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2byrsquks.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2kjagnbqk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2hkidsejf.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2ddmkoeck.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2lljxvqor.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2atfsfeaf.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2qmbsmxdg.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2yoacbiue.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2vaemfsgw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gt2yyclgrxg.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2opmnywkv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gt2qkujdmfi.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2zleczkxr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gt2kzqueybx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2rswvnrvw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykpnrxbf.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2cffhpkvp.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2drwedomz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2jrfwlgul.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2gxgsvnqj.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gt2cjczocoj.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2mtewpuql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2nkobaaqj.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gt2ahxxczew.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2kgawlyil.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2rcysuywg.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2sowzuova.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2pwwzwgdf.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2zrhblutx.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2unejxabr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gt2farsxbqr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2cjnqjihf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gt2nameuqpk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2adifsntj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2mgotvahs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2nehtiims.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2knwmctqy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gt2iscgpdxc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2qpigmayp.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gt2fghoocfa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2rfqetuwq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gt2onlfaurm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2alwnyalh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2vvkkfryb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2hdhavxmu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gt2fkakrqrj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqftnwyw.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ripbbxln.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gt2dlpdfbti.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2idsmrsoc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvwqqccu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2kqtelmzo.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2zfxonesk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzshlcqs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gt2ltlzhato.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gt2pvkndsfl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2obzuclto.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2xahmhfpl.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gt2egylwics.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2nevidyis.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2igtukwmi.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2odgsvlhb.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2jdfizbes.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2kcylomoz.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2usbrbggm.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gt2ozchnzgh.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2qjvsoemj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2iajyjfbs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2jrvyvnzq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2pnnoezdw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2lezsbyap.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2nhkullri.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2rhulguog.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2kdwmsowg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohxabwwb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gt2cbdirtbm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2whbeloxt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2bkfqrkfs.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2mpgfezfd.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2ryonzqxq.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2alcxolpz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2jubjbnok.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2snsiupwi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2pljopjen.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gt2daxeynlw.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2fnruxpga.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2doxhhbgh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnjnroe.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2jiwvrvxl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2qcwjfwnn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2fyopauvi.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2mhpjtehl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2wwqgtlrd.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2qnzmnohp.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2zjmleglq.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gt2hgiijrox.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2ixtuhwko.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2mktdkeph.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgipegdv.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gt2wbddbqab.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2sxlzbcgy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkwilzey.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2podqpxnd.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2fladpvjh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niltjrgs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2dxlnnuue.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2ktunskip.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shyokzij.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2eikeiegp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2fulqcodf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ibkmzzii.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gt2xmjtinzi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2jnwqcccg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtgytfks.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2qckspmeb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyyuccii.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2uaaecbnq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gt2tjlavsri.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2gyeaeymw.html


<!-- 参考信息 -->