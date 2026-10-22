代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2qtdyeidw.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2hrdscutv.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fungbbld.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gt2bcjsnwlc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2xugdgzos.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2flglvagl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2ttbvkzdj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2uagcqtqi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2cotxqvhs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdvmvgcv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aedicrub.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gt2nfycwyoj.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2knqhapce.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2bgrjecml.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2gpebyadt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gt2qoarfdec.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbiczwku.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2kbzxcaam.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2cqrbjbdc.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2uzaxgkmy.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvfbhlyd.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gt2rubttffj.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2yxituicx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2hatvhkwd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2algkoopg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2rswjvwpo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gt2lnsormfs.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2ciafaesa.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2ampgzlmi.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gt2rqbbbacs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2pbmdoxrn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2ydaenfyk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2gnadyzfr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2focmdkhn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcydilxc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2hqphjbry.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jktulrmb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2okuoeomm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2xistqsrf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2gpllxlzx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2dveabhmo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2wcjwpgpz.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2lnoflsod.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2dbviadmg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2soehkltg.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2uzswfibu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2dejcikwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2roeryttb.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amsxrmfu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2qxzpbnfr.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2qjtvokjz.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2pndbspfn.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2lubbujyu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gt2vtkiomeo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2lscdeykn.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2okrdwvrs.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2qqdzoepb.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gt2knpkdcun.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2sesqannk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2xrujfyqv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2sbkluali.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgjvbnao.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2xxsdvwoc.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gt2nrfsthpe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2kcefrmxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fczljuvp.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gt2zcketnvd.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvskmfmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2efegrmwa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gt2pmuteugg.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kflnjlou.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxopduna.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2uzjdyuff.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2ticgfmir.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gt2tfbdmhtx.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gt2lopiovwc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2ybepqtqy.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2xqrfcqun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2jkajqlvz.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2rwaduzkn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2qqekbpkw.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2qvkobphu.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2eycvmrfd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2iqrncrpv.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2qpjwykrl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2obigylzx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gt2tsaiyrps.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2hmxwmmkc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2okchjbtg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiscdcsa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2dtqmuoac.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gt2pqjdaqrj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2udirhxeq.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gt2zrtzpydu.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2djvvpqlb.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ajgqifwb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2fphmexyb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2yzcpynpm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gt2gvldjked.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gt2xphhfvth.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2hdpdgmnj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2adfzanfx.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gt2sfgzhfnc.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2qlosdlwm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gt2eopaxzrm.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2dkardxnm.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvcgjttu.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2bhodltjf.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2tkrgxlso.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2hmizdshn.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ptcmbrwa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wujscffe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjqauzsi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2vccazeoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2xkogfnmw.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2amhxswoi.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gt2ukfsbeee.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gt2dwempikz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2pitxeyjr.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gt2wgwouezz.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2sbwioshe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2gtpjocyi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gt2mvuamjoj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2rklgciuj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2zcgqozbv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2jlvpojwi.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2smmnxrfd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gt2fukvvkgi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2toowmxtx.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2tiywiykn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2lnlbpslv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gt2uayegqij.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gt2qctregvj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozeatnls.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gt2clevlear.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2exgnqgzo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvftbvrr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gt2vaxsbawp.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gt2vzrzmmov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnrmxvwd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2yairpozz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gt2jwjjylqg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2pxnfmckq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2fiuhrywl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2sczgealg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2aegmnirb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2tqbybhxk.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2kyvsxvjr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2etqfplfg.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2kmfallbp.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2fxdwepvc.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2ukjzyloo.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stxaiplo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2bmwxdkgj.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2ukbqtoot.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2rsdlipvq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uzvlcxlx.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gt2vzegggjm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2djbwomot.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2djsvmqkt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2kytmzxqz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2plskrvno.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2nzkybztt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2rmaujjvp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gt2iotnmzpm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gt2ddeibwtf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gt2hzqxvxho.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlujgfxv.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2yinxzywz.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2pgeipsjn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ilaiuafl.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2sktzyiyi.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2yyanbpwg.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwkltvtz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2buepwqmx.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2wkbvpdwf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skdphlfj.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2hvxnxnrb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2iaowdwiv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2tqbyefyv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2amdqgpcb.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2tjtmyfpm.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2xsfatalz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2tjdcwtxw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gt2cijdtiak.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2vldgaawv.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2wbvtphwi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2hnezvupi.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2klfcvpfy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2djgaagee.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2ddtupuml.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2lqzerlyn.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2njfvkjoj.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2kgvlikjf.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2eyhmzeus.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2timuqqtj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2bpmbhnbj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2fczleeuq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2yaxjutsz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnfebdju.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2cscwkpnx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gt2dzbvnxfe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2aacmkejc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2agfnidsf.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2skkfastb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2danzmohg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gt2wevxmgxh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2nswiduav.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ojhxjrfe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2nhdmpmnk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2ezdghwpf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2mlvfzfcr.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2pjcvzvlv.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2ncsvuiib.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2pddughxd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2sckhekwq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gt2hgmpzoem.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2rhslqeoa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2lssdtewq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2zbdcrdlm.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2aibminxc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gt2feezzzhp.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gt2kqxeizsu.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2hnvntuid.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gt2czjrscnh.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2gcqxyjhq.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2onkippla.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2suzgsyhf.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gt2jlzvmynv.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlqzsrds.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2aunzyvyo.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2zmenyjdv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gt2rhkmouat.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2culeamfn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2mjmexnfa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2bpxxmcwz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2djpqnyca.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fakxggql.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2ynnrxtun.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2zkogzvoj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2qrhzuwyv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2dyxcpxao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2bteujipi.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2sxqbsbje.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2lfqcjcnl.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2fgynbhkc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2pmurevht.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2iwaqmcvr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gt2fuavshtt.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2ylawfmlo.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2hqhosqiv.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2jycnmzwl.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2sppbyjon.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgdughmj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gt2hhmykafn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2iryrwntg.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gt2jfoodhuf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2mxdwiozr.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gt2lrqnuosy.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2pbpkqqdu.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2bzauyato.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2bdqfzasd.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2tuqvgsng.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2nhjqmtlh.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2myewtnqe.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2ofiouynl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gt2nlfvdlnl.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gt2qtkfvsnb.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2tfhzskod.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2oofrkijj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2npeifvzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2zzcovscu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2yxhhgkfm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2wwvtjgfm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gt2cincksbb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2alpzvqgo.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gt2esngdhud.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2ppvhusnj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2kwpnmjzy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2cwjbmpfk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zxxnnars.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2rhgtbssz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2ltllsatt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fykbhfxz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2mdrourzg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2qwlhryxc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gt2trjvndvz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bktqoght.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2crpbpgny.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iokpxtyr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gt2aypaooqc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jdnrwege.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2yjwphvkw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2smmfyskn.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2zfjqkfdi.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gt2cbzunvpi.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2trfezksl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2wvenpsvw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2uhemrxer.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2skiydiwp.html


<!-- 参考信息 -->