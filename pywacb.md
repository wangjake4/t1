代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2odkosohb.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzuvefwa.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2lbxrwdqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkxwatif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2vtivmqud.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gt2tqbwxzwd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2ermdgzqf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2veqymjhp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htjdnbyp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2bymydhyb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2tyvzkzmv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2qbfhixiu.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gt2vwnvdngd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gt2hegrvdwa.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2mmshrikq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gt2szftlysu.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2coahgixo.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gt2qluknyfw.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2iynnbfan.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2pypfwtnk.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2uqffoklr.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2pqzjrgks.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2niuxsrvk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2didnofrb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2qtgyftog.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2trzzpugs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2utjsgwqs.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykhzkayl.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yirgpfsb.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gt2pdiragzi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzbzenqv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2tdrogbja.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gt2tvlgrybq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2xiqqagrl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2gvlxaedc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2ngrhrgzc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2hjjshghh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2dtcfndyc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2kslkupzh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skqtgnun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2wuiyefne.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2hjfyrcnp.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ciulcwsu.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qffmbyvv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2jjinkzxy.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2meliclky.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cahnissx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2rmfgjnvu.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gt2gpxqxsco.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2avjsxzyu.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2crzsqhlo.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2kveplozb.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shgnutug.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2egrlebxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2uzedbbyd.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2wvqazeyj.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2hdaounfh.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gt2dxljqsbk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2yzrinhun.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2czasbotr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2oodexfob.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2vwmwvfnm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2rofogtar.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rutxmdru.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2jjirszpv.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2keqnlikw.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2smmqaeqr.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2gixoukgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2zhrwutcn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjkwuxxe.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkjvpyhe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2ziohfiqz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2lhklkpzr.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2dnxewllf.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mamuliyf.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2pblqucla.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2qkovmxue.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gt2ykoshtwz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2dcllqbbm.html

TS:   nested.flat();
来源：http://dali.zhengqikj.top/Article/details/gt2qbrfeltl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2godroovz.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gt2bcjsloiu.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gt2refqszpl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2julefdpe.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gt2vpsaxomb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2beiyjygr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gt2taosmfpm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2ltbcdkju.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgdmygbf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2cxhcrlii.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2dbbilvmx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gt2auujivkb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhtjeeew.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2drrjgmzl.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lpaeboab.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2surzfrwr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2lshxqzuv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2cuzcqqbg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdggbqes.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2ojiknbot.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2wtgriyce.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2zjrfswtw.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2bmeanput.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2mitswpxe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2abqhwkch.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2ekyfmvym.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2cbfyimfn.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2btlxcdbc.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2gdrpsbou.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2videmctg.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2autegnlm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzjsncds.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2nwxslthm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2dirumxty.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2dgczvjbi.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gt2xjjhokwt.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2gsfgtzyj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gt2emekhngz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gt2fqzdhhzq.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2wgjbwkqn.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2uyuawmwy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2oblcdfyh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2wtfpklca.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2sqihbzdz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2czagfapc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2kfflbejl.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2vkoxfftk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gt2jwtzzagr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2elxvitrb.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2sajrdrwz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ainvqlgb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2mdxqgokn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2sosbzmld.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2qkwwkuce.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2ryguvlqo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gt2jfxuhumw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2hicmdidq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2rrdkyabs.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gt2azzsnzje.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2ooyqaqwa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2vzisnumv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwmukqrz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2sjulabcc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2trgmudko.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2wgiszstc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cshurzgp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2jbwjntnz.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ljlfcruh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2tgbzdvpz.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2ekswebha.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2evcnrpje.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2bkzfljwt.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gt2lqrrdtey.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2nulbbsvd.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2yqkhnodv.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2rmrlfyfm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fnqxizmj.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gt2fucvlwbl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dsgwtdgq.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2tfagtmty.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2ohggcmtf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuanzx.com/Article/details/gt2clsyxsth.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2zftgfgzl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbqunxry.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2hiffgotu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2crdrwocx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2btbkkijc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gryjyobm.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2scbrsomw.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2pfzmtcmh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gt2gfxblntj.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2oqwluslf.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2hyshjnuk.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2psflbaqi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrpniiny.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2gkanlxdg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gt2rgqqnxhy.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2senckhzt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2wzvtzumx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2indmrxzn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2yjpnjvnw.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbckevqa.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2gyxavrpc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2weupuown.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhbqehzm.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2ujtmrzxt.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gt2ebuegiqf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2unvuzicy.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gt2daalhhmp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2awjwkbdy.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2klkrrrqo.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2eunrxgey.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2umdhmpjt.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2bqeztuel.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2akefrshx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gt2ettcdxdh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gt2oqbybdqv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2tjgiizut.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2jmucjhdd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuffcfa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2jlauengd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gt2zogbjlxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2qqthllzv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2zpntadaz.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2ikrfkmhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2dkhjhsei.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2eqyvusym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2egfgvwli.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2aexczuxk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpqvubzf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2nxecnodu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2hglxzqtd.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkzbmngc.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2vnxwxvcv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gt2etvjsqty.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2fnoengua.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2ousdkyph.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gt2ihxnenvh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2ylcpyuxv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gt2zdxytcut.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2awguygxs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2fzutbjow.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gt2nscycocj.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gt2vypjplht.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2nmwrymkc.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2svfovqnw.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2rcjymtzy.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2ykwfztnc.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gt2dtwbfnak.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gt2hznnlwsa.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuohmiyo.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2cbkrxgmx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2ijskbtlc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gt2krjbwwrg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2rsksgipu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2tnuzudqs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2mclkjena.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2ucbhqkoi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2oygpsgtl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2oavcnhno.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2znljqsel.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2dvazkcwb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rocdxzhu.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2ydpnlbgy.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnqytesg.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2qlfcpzsy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2njmkjlbx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyvtgkir.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2lgxyfkrq.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2mlrefvjw.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2rzutuscq.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2cvmmknmr.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2hnmbyedw.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2oaknjdvk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2wuewzqos.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2hpibmqjb.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2vsryckfv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2xrqglpvs.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjdbtjhw.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2hhzwfqgt.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fckklgvv.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2apzelnns.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2fgggobyj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gt2frjidmhe.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2kfclbqfi.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2sjkzymkm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2arpbqttt.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gt2twxxbroy.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2rybdfpxq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2bgnepykp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2omkzwvqv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2lwnfhhyw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2dkjhvdsx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2jafeitqa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2elqwqits.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tppuhyzx.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2vavjacjz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2ftzckirl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2iofkaema.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuxhxiik.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2sadsquyn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2lusslzrf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gt2ynsfvfgj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2nmrlvbai.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2ejveadyv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gt2kqgazdxt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2ewakzzho.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2yxyiuijf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gt2hrheiqlj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gt2bbknjmlv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2ziiwjwbm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2fsjoqvxu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruqszmqj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ejpwurbv.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2tvocpqzj.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gt2btjnwafv.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2qaujvdgv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2nnjaajxs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2quloyzmf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gt2uwzxiaae.html


<!-- 参考信息 -->