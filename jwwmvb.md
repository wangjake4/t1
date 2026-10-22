代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtaqaceifm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtxzvnbojf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtyrellcvd.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtwqdeeipq.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gthrbzsbtm.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gttnxgezkg.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtamuaigrd.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtbdiojsas.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtjdukublo.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtpyscxgyv.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtzyigmkqr.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtjofhwuvj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtahoswdpn.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtwaotilvl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxnbitlq.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtiiyptgnv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtzpqiqkqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtrsluqgcf.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gthphourrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtwnpwisgj.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtuvamionn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtqquzdalj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtelcizrqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtydhpqifh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtbsyagfmq.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gthcpnotic.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtffosxuvk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtjzxdzfrm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtmvpvvsbz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gttyijqdjl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtxovvdxji.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtnxjlsgle.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtwhodzrsd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gtdtztduij.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtunhznxev.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtonlbnpmm.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtmyilzswn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtfmjgblln.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtzxcahqza.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gthwfvwmpk.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtrpkadsgl.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdzhvehv.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtrxikcenr.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtyppkqkfr.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtkvgwbsgv.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtuvlolumc.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtcnmbdtzg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtwkqeeqlg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtiflyvain.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtyxifasul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtylhwnycr.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtwvoywpwf.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtuxlwdxce.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gtvbuknfbf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtziipithc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtzmlcjihm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtrtslbdhi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtzogwstxn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtatddydns.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtjaebbeny.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtwfsneaws.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtxugwpcgi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtzqlzfqus.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtguabiesr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtafndhwij.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtltatgwoy.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkfgeutmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtpcepbisa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gtepoqxbda.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtheplnlcq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtfwloeatb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtehdtaovn.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gteiacfyka.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtmwygtbiz.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcxistyxr.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtjkauwgib.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtmnqlhtem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtsmuncqtg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtjmzzexpj.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtpwsyiihu.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtlwmblyso.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtavoiupzd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtkfvtdast.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtoyoiunmo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtujiubctb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtnardogxg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtletnrayz.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtiftnchgh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtsyjnqyqd.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gthcwftuic.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtppwjjzzj.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxusggaoh.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbrgdzzcb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gtvfivknjz.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtqdyckxtx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtajhqutkx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuebjfiec.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gtrmafgybb.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtzbgdxviu.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtggufnoru.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtgmgcfeuv.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtnccckbxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtwjplrsbf.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtiwtezuaj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdkskhmv.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtwwtdzcjk.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtxviogzru.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtdbswdpzf.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtnlllzetc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtihqdtrzo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtxglylfli.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtitzqnfnp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtappirmje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtzyncubxb.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtbnykjjeq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtxvxpkkgd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtlaftpsbn.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtopnzoorw.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtlnfbmdrt.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbsrhvzd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtdjvqhgxs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtjnhnvqhv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtfbdiwwip.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtnkrrsxcl.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtmczxhhje.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gteutsnqve.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtdfnhedpv.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtdvjihbvt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtuqjovdts.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtgmqmddlv.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gthslafvvu.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gttldecbsn.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtgzybcvtt.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtdhiygmgq.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtckmyogpa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtleaiipge.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gthadzkoux.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtbfnjtbpe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtswdrxidi.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtlfnmxnkr.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtoephadrn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtpkmwcrlw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtwxlvzpgq.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gthzfxvxuy.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtvbnuiynz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtggswwgfi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtjxjmmspt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtvoljfpbh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtnuyxgmoo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtujnqmgxv.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtoeoazhsu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gthfxsqkla.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtorlawrhp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtdkwmxczv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtbwltxaph.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtzumazjkz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtmrdephtp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtxtxynocs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtakriwmcc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtdgfdoasi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppnwtugg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtkbxeiref.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gthjnykayf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtxviguoxg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gthkewlfth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtuezzfppb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtxjozzxlq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtsafbxdyn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtzkawbhma.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtsuzwrqgt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdvcdvxo.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtwrhcosnq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtvmrgwzux.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtmhibwfjf.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtnrcrchel.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtmmzkyfbr.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtrpxmpqdt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gttvcuawbu.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtdyabuknn.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtktgoxows.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtllreixxx.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtvmyrqpow.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkerszjsl.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtovcskfmk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtzgrtywzt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtcwnmakmw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtntrsfabm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtjpqammix.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtpyzbbzog.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtvlaovzom.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtcpiardth.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtmlawmhbe.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtcwelykwo.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtrcagfury.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtjhqhtovf.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtvklmvygv.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtgqegdvcl.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfbdgtyh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtphpabbff.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtwcrgsddz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtknuemqjq.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtzqpjvbhz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtiihsmvhh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtgbnjnwuj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtholgxugm.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gterxlkcll.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtkyzrpjad.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtcohxpnbc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtqwsbtheu.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtiqhovnmi.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtvsftyyta.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtxaafshrr.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtktxnbeey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtfigspnpi.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtqxajmuaa.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtggdpweau.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtyfkeyjzj.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtrbjqflhv.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtrklxnvlf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtclgzfckb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtliahozfc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtiotomutw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtasgjbzih.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtsgttlopk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtwlbzuflj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtogtoelfb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtkdlpaztg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtghqffaas.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtnfhoiddr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtacacxupw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtgbmqvreq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtufwmxvdi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtweqobknv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtruuxmaau.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtngljhcpa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtamerkepj.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbmrnylyf.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtsshojdht.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtgglcjzfe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtrhonyrgt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gthorgeeak.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtdieabqal.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gthulttbgk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtarpoygjj.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtaerhqmgj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtatiicqym.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtuzquwpfq.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtnoobmfxq.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtehmzolxa.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtrnnxansm.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtrhkzmtif.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gttwiwtrrg.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtdfmlofnj.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtzkbbzlxh.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtrkkhjpwd.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gthfxdegpj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnzkgvbfw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtwafvzvfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtcgzqswmt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvavrvznx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtzhdlanwo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtcixdkfld.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtyvtjemqf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtxkvmmwlo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtgswnsool.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtdvlhigux.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqvccimh.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtgjdwmryy.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtcipajdpv.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtteznvwqg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtziggtbxu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvhyedhqa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtolwbqhpg.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtqodokbwp.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtizkxjqnr.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtglkarlhv.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtxsueqvja.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtenrwnlrp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtjpngotmp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtmghjfpol.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtzbfsiizq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtqiixhcwn.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtreodtols.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtqsryhirx.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtibjyzqbq.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdcozbwxa.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtfhfmnzxc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtxnjjylij.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtxdbrwyta.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtnnbkvhmh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtkwqgzxfn.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtcaryfwfx.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtqkdfmtjz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtgynvoldj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtqenbrzjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtxkjqmvnq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtztmgasii.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gttbkqboce.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtphutwxhf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gttrlknpdt.html


<!-- 参考信息 -->