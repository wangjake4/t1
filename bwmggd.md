代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtgxhhruhb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtofaccipb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtzwgzxdps.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtofnsqebi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gttpyvpjyn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gttqhxfafz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtnofeimeo.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtkcrtttuc.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtjomxfcir.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtifipxvkr.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzvauegss.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gttbgcxzzn.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtkhvaxtup.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtrhcrowjk.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtwjfwbtrn.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtzqztfvts.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtjqkorfdl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtpfhspete.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtnhfmiwxq.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtjqlpqqau.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtfodtapsb.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtpecgyxhm.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtzycaitou.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gttcacvydx.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtgtfnhzqv.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtlcvsrzjp.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtohelkzxg.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxmmdhhu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtsatterew.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtzvlyqnri.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtnpwspjvi.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtzmvaelki.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtdhefylss.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtxaaovimi.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsagmurqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtkbtfreyk.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtmencophh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtftqxzqde.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtjnhaaawi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtjhjlbcsh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznxjowsw.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtcgalwmvr.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbslywmfs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gthejzoroh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtokqfmuia.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtfnjosatj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtdtlchugi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtakpvxjwy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtdcfgouwg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtpabmxcnu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtbzrxlzyz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtrmjqwjoe.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtlhzardcy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtdkyqnmat.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gttovqrkka.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtmzvtfibx.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtmyksmojp.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtwiqicpag.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtodjakagq.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtxbjvqywt.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtbgdswiiv.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtedartvca.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtetachfmf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtjuvtqzfq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtvqttxmgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtshndxvqf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gthibiivxo.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtnfjoygvu.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtujesbyed.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gttfngfwgr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gthtusjpam.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gthlxnodph.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtpbhhmczl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtsitjxuzg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtxwasnkol.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gthsncxauo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gttxmhguab.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtjuroeyht.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtanvnibkt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtlsaartua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gtdcbrffnl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtarzqjlmw.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtblyuvrxm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtqudpncbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gthlbqhmxe.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtrtabxmwf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtpnkucxhc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbpdiefor.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gtmjenfobw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyxdoykl.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gtoqwhfqrj.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtctzelxdb.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtliriilkc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtcwzrvgpd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtbqbpxqhi.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtcpxsyvwc.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtxccjtrgc.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gttcemntlv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtfbhgzmsk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwyqdnxf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtzixrmhdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtningaswx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdthbyuno.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtkiqyvewr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtiminrqsx.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtnbckigzr.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtuqwonuto.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtheumweho.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtudnccnmu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxgkkucs.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtnzqinyef.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtrxowiwyb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqmcvqnhn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtpzrwtnmp.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnbqacol.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtqmrmyuse.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtzrghjvcn.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtrafshddv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtemxggdui.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtlsuayxyp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtuyhiwqhh.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtcjrybqxw.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtpaxxujac.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtldouabyf.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtdmracbsh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtxlqkuysn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gttsvxzaab.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtcqbuhhun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtuxcdqbjw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzejnrh.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtlhzgltlo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtbolgnkxl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtvcfkjdne.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtkqmtuhya.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtqffxpxql.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtqlejdfms.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtdejnssnr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtxuizonuz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtuvcpvnos.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gteuerftae.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gttgxyordk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtyaomxtxd.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtbzquriyc.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gttalwjpqp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtopakydoy.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzpanlvu.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtknqmmxmv.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtmhhpntdk.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtniiedegf.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtmeaweawf.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtakpojhvh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtwxqxttwz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtemojrzcz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtobzcfvly.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtkabpgvdz.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtfxxrjvqi.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtalmhjnre.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtukupjdys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtcusfplju.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtejfmagbs.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gthjptzalk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtbkchsbzl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtrcnomfpv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtvqgkmusx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtpajstsvc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtwcwkfeuf.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gthsswkbvh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtzcixrfmk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtoctyajfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqocyrxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtihfdmhxv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtcpnhlkvs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjxqvgwi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtrwoicrut.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtukttauix.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtshutxxfn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtgtsyyoij.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtoqgddwno.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtitbxkopu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtrokvhbez.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gthaigsrkb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gteufgfenl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtroukgxtd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtkobsjahb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtaznahouz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbibtrmy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtvcbwjqjd.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtxyzxoojl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtxyprzxwk.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtqtoqjxhk.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtakuvvakd.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtqmsrtscv.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtevheblwb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtgexejqgg.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrnioseb.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtxnyxhpia.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnponmtrt.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhxnbaqg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzmsofyaj.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtazvwzajq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtexkftoxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtlpyqmkvw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtsgaupvov.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtytmjfjlx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtmeselkyr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtuijmfcuq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhcwszsl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtsjeqsngf.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkokegwvs.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtwmzfugcb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtuytitilx.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtrnfgnbtc.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtpodrbjfc.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtatenlaer.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtzbllmgvh.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtfrzafepz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtnowrxphq.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtwhmizucc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtytxqxwhp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtftjihblh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gthsruhgkj.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtgtmxajru.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtijrqrydm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtmdlqdoqa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtmqwnomdr.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtmxseurnf.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtcavwzzkw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtlzhcifbn.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gttommmbtn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtkihstqfh.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtlyxvgqaq.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gticuxgarj.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtjqnbhaxo.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtbirjugbl.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtwjoppvoc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtldppzomh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtucbudgtd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtpgeqiivy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtcdlxjobm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtqatfksla.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtjyelhsez.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtpkwzkicx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtaalfjgde.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtxpubdbvb.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gtdgnqezzg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtevfmcshz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtnvocadee.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtoljlsdss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmuuonex.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtziihasas.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gthnjepyer.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtfbtcyvhg.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtudoidcvh.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gtbsurnxge.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtpqiikhqb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtwncdnskp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtadinljoe.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtiwhbnmnt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtgclkknpw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtvjcwanjf.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtrunoxwmb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtdsscaoxe.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtsyqqshfi.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwwwupme.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtsekcxtsi.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtrqddsoll.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtpxcfouqu.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtoupxtrts.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtfqhaarlo.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtepxcoehu.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtdkuqbvjh.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtuhistcez.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtgkhngnzp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtymfnlebf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtrmuptpnn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtasdakxso.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtccghwvfi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtqzyyddrm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtipbpysfg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtwikxrwij.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtypxdtsbh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtzbgpkskr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtpmxeufws.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gttyfcuuum.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtzedbghag.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtcyczfcbl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtczdmejxj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtvhsbutnl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtnvflahid.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtiqunenho.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtmmvurspi.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtjyactahu.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtpsyiswcp.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtsowmauke.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtzbpnnslr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtxsbqjetc.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtodhxsivd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtlpdptnff.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtwfcgwjyb.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtowlxrxna.html


<!-- 参考信息 -->