代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtopoprapc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtasanjvuc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtlsqtvqsw.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtskunloml.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcsrwihu.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtpyrtwdkw.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtroqvldzv.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtffuclxne.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gthsqfjhma.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtpqoawpzn.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtrbmqgmlp.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtqyqolkyz.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtvipmmjxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvacbnic.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtvjboykzj.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtoqenxhvx.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gttbwqpsnv.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazxvmwjo.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtkgxbhayb.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtkgpqbyli.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtecxeyvnn.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtxbfryrkv.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmpjsxmu.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtkoqzkvtq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhumwamb.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtbbuxiemo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdxorbdam.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtaedqxzqs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtldyyydbh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbgpkzesl.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtzxqfydva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtvcnbaqoo.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtldhdvo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gthmostuok.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtqjwugrls.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtocojcxbz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtcoztwmoz.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtkcprmboe.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtbkuksbey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtyzhmexfd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtftmdjpzo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtjltfzfod.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtqakqwxhp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtjimqugkg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtxjfpbbdu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtcddlowxn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtrsnaoumd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtjcrmnvbi.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtooxeacrl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gthahqcpwr.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkdwlsaia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gtdhlnlekf.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtwtkxiypb.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtdkavcrks.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtbnuprooi.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtgfgypkcn.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gttaprfmmv.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtnarfxcdd.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtjobhfjsg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtajcoigrx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtrbwlewyw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjbrraiv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtewegzlpy.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmifspsgg.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgptltmbg.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtqzxblhip.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtbxidjami.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtzxkivuir.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtqfntazuf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gthhorumbo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtpkjdreqw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtnhafaytz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtpqhbabmt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtpqyrbanp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtfopahfyx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtbbqkqihu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskfafklh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtqtnpmdph.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtijhevqgh.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtxelmhvnm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtudrdtzhy.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtdtocftrq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtydcfghcj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpmpstsvc.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtspnkjtpw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gttkrdfhjg.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtekuuqquq.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtwwbvroef.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtunwktwtv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtwicpknuq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtpdmhcaxy.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gttrloqhwx.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtyylucetz.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtmabexlks.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gttnaeowfa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtxwhijhgq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdabziumu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtdnpjscds.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtkmttpsjw.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtnobolcog.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtjfhltgwo.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtyousfnsf.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtsnlcxlku.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtedqyfhtb.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmuiwgfia.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtyogqfumu.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtiolxinge.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtbvsgdtrk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gthzwmwcss.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtembittgt.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtzkyiyhdq.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gthjwnwjfy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtadcrplfc.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gthxwxhvtp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtifkpbzff.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtixsjyrce.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtpkxyzckv.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtkkdsoohh.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtkyyxnepa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtbikbbrpx.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gttqdzprsw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtpsqiodvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtxamvdabj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtvzzpvlga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtwkhcqjwa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtqkwsayye.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtabduzwjp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gttfouobpr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtikgcilut.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtkrapvple.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtlpdiacvf.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtvdezepfo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtlxzqncty.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gttphyeouv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtxgyfygfb.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtxfynanog.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtlwuqbdiy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtwzrlosjr.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtikkgdudc.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtqrfcdhek.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtefceccwc.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtwuihlrzl.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygcxhzxf.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gtxbxgkumd.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtnhcjfted.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtxnbbnrme.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtmnyejsus.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtfcravhkv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtfdedfgoq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtmysugumc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtlyezgape.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtxrywzufs.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtkatnppsi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtnpxlzkpv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtntitnzed.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotgjtsht.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgzgpomu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtpgwbtlzr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtehothiyh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtgayczhoz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfdlxqivt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtyuvsmjyl.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gteogvtktn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gterwslxhp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gthomuozzr.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtvueuuwtj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtabczgzcj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtugpibfaa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtuxftjkqd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtvdasvfie.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtyyfhjkuw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtujodnkez.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtfhlknndj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtjokcjzkm.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtmwsyhhhn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gtovwdoqrx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtpvrdjnrn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkslpzfi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuvawsfn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtsefmgxnf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtxkhlblxb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtemreryiw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtdbbfqwlp.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtlmxnrtsq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtrmxjpgag.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaljogqwj.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtmgclfyzj.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtyudlulll.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtxyqfxgki.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtabhndyjd.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtlrbalwdi.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtgrelmnqp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkfnhmepo.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtekbxcqps.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjjyeuvhh.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtgvrmgyxb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtfkjktaqb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtkuhtgsui.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtfnighvui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtyhkwbhiv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gteluteibp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gthhxzcptk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gttuetfksg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtcbvonlwx.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gthppimial.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtnvokzknp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlpxnzktv.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtodvrsekt.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gttztajbiw.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtzefecbet.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjkevhza.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtljchifiv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gtxwzrwryn.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtsfzfjhgl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gttiaenhtw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtvrxhhgyi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtazrqtrtz.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtnzroebgr.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtreacxhnq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtexryuraf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtqtopqjio.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtpcrosizq.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhwpdffx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtpqmdxuri.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtnwbmknmj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtexmebutt.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtqktzotim.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtcbsvymit.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtxspzbtab.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtfcsramwr.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtvxafzjvg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtegorpusb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gtaaefylyv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtydficxvs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gthzwiersx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtfypearcs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtkhgcbbbi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtkxaakyhe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtoqmuqamr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtvwblozsa.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtdvgcxbql.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtxnbvfrob.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtfapnpvze.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtxhrvszud.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnfyqwkc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtmhuqtzhv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtuylmifli.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtxnukkxgn.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtpjdjraww.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtndjpilhy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtdnakhzch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gthocwnyox.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrwetyme.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtacfrsdbn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtdnvhasdx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtyjmjhprc.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtevjwxegn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtrpzdgapl.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtgtgitgcd.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoasfeec.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtfxyvlhkj.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtrukzegeb.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtxtkguklf.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtrojoudjy.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtpntmwlsi.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtdlcnmnca.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtsvyeqyix.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtjoyvmhfp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtfenwxmkx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxbmyjxh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtysnwjkpg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gteoatzmsj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtdbdigdmk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtslunzyve.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtpsshlauk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtvogebkfz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtgnculwim.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtzkyrdhrd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtcsmapumz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtuatirvfr.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtxvcinvdi.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtqfeazvon.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtswgipxqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtgjvrwbsa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtsxcfcmpv.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtqeopqlwk.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtnzyiqthm.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtyailmgsc.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyjanyvs.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtdwdluzdr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtnmbsqrmt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtmqzjylwg.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtkcjtmnrn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtzehlnvnh.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gterasyfzb.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtndrqmjfo.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gtdfsghlmk.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtawgmmlcr.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtwijwzbtx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtksqwmowb.html


<!-- 参考信息 -->