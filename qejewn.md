代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gt2uuylrogt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gt2qixkgkjg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gt2grlwydet.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkabfcfi.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2ophndqyh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gt2veywgtly.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gt2tdbaxlua.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2hrfbpprl.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkyaregj.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gt2oqkrklut.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2wultfxcb.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gt2iedvpxce.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gt2lvkxtjcl.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2wqwlmzfg.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2qgkkrznv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2kttwnqld.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2gvpgbgwn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khpnadrc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddppehoq.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2sjhgotoz.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2sqnheowc.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddnbgslv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gt2wvcliuii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2plnkeaof.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2gxomohzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2verfocce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2psmlbnmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2jdtnmzph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtwyywyp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gt2xilijeuy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zufkdsim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oytsgkfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gt2dcjvvvjv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ybyqiuom.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2ljtqmazd.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2gzasdfxn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csgfehsk.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2yyacqvup.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2bekgkqzt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hwbvrjwd.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gt2ljumdwoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2gmmhordh.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2yotetxbf.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2rxbagehk.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2rgzrefqs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gt2txqaexpw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2rsmxylqo.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2ihfsjmci.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2meskcotb.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2qsntepqu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ztdnhgqe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2kmqrbxpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhrptuus.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2javzifuz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gt2zxcmdwau.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gt2pndguvxv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2xovefxyz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2pnncjuzh.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2tumgrayg.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbeyrfiu.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2vgqhnbus.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gt2wwzsahts.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ismmpuwt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gt2qyzrwgme.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2upynjdun.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gt2orbushxw.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qurvwgkw.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhzqsier.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2oxuzqpkz.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2sgrnsudl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2roflivhl.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gt2erapxbkb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2qhxvaqvy.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2ufssahzw.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gt2cqijypcv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2vuogblmx.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2lxgfubdp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2fwsraiwg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gt2pfxehwgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2fmustdjt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2fqwnoaut.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2sbyvuokb.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2bwadidey.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gt2dvdrpmbt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2alwjljwi.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2uhllpgyh.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gt2uiarpona.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gt2emywnthi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2vjmapcun.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2puqqzqae.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gt2ilejmbxf.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2oculdbcp.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idnxngfp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2ermuwciy.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gt2tzgctnvp.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2oulvhxxs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2vqoiprvb.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2pcspeecn.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2ijlvexts.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2hvquxsdl.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2eqievjvd.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2pxaiovia.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpmwetcx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2xqcghknw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gt2mpobfqfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gt2hjkpwnrd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2dikrnryv.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2gsfyfqgz.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgmyfnrs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2emkhqvtg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gt2fbqthoqc.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2ghroxyij.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2kbcroymu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2yjvrensk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2pzqhjzsv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2uggossvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2cgmdxjey.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2lrbuxzol.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2xvdorkyd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gt2phwoihev.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kplwmjfe.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2sxrntbxy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2kwjeblam.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gt2tamlland.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2xnrzgkvj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2turauaac.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gt2ftwxzbfw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fixeclsw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gt2zwsexmjm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2ceyhrohf.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gt2vbcakakv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gt2rjkqisem.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gt2sdmkyodz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ihzeqvjs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gt2gjqzfxkg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2fijwemoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gt2tbsjqdun.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hckiiluw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2oxmodyjn.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2pkilbeiv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpizldqx.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2gwprjfqk.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2eyochykl.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2bdcvccel.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2nwmpzpgu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2akhnfbpi.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpykyncv.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2dzqytpga.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ulrrvrmh.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2ngdocyrp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pxljgpgp.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2wrccqvsb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlfemzcb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gt2gzjwxity.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2vojfppyh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2scrhwunq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gt2zttzwmke.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gt2ojekraiu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2jeigaicu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2tsihvhng.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gt2xnycwhkz.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2xfisqgmb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ivvv.top/Article/details/gt2tnijhiix.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2lgbtroer.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2gfuksmia.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2toyqutaz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2olgionud.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2poshibct.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2ncnsgtup.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gt2ezphvbqb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2xaihejuk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2uacmzjav.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2hhudbrsj.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2sspvhqtj.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2ykjsqejk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2nkqpcwtr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2qlqksmnf.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2bdycuabn.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gt2qxcgyctl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2owtazdhh.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gt2chyutzhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gt2xjymlcml.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2msswlqzr.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2sexkqnwp.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2sngdjqxl.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbbwaeha.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2pcnwksjv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gt2lujimawz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gt2sinwdgiv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gt2vuxquoyr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbosbhqz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2fojjhakt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2edrvcdmo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2gtbnqxgb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gt2fgurllcl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2vnafjcfb.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2sygqaxia.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2kskijuqd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gt2ndnpptcz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2hwwplsyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2uifjiatp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2hgignoam.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2slnzqhit.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2dwdrxcvr.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2wjutkzid.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2zpmujcqn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnuitkao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2icwkvkjz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2pftdxeuo.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gt2iqipttlv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2ghemsiwx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gt2nkpgbknf.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2dwmzicaa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gt2tnownllg.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2bduoneid.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gt2tdzckfrp.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gt2sixersnh.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhstmhxw.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2tukpnsnj.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2exoudkzt.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gt2uittqfta.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2mdhghsra.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2ylzurpcx.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2axcvfzvh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gt2iejiiaje.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2vwsgltco.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2dvgwmxyc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2cuvnsxhx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2jlczuhmc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gt2amalljjy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2jftkbmzs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2rccxryvl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkqhmfxv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2bkwpvsow.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2qxtzmtpw.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2svlynlps.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2isstzykz.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2woznzndo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2trgidlmx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ijqerlvz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gt2gwrkpsgm.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gt2jqzpylgo.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2lxdlzoch.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpldmayg.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2sqcbowmh.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2bfzamgvw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2vugnenbz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2uamtxuac.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2cvhxpnrg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2oycxeebg.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gt2crikjxyc.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2zuqlkvkt.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gt2mgwzesjb.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2huvmtqoh.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfxxjbem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plivdron.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gt2flfuxmql.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftinkvyv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gt2zmxxldzt.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2obiaikwv.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2pnqkrfmw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2bkuipjip.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2fstxbwvg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2gssypown.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gt2xvspnpge.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2despzlyg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2reydldls.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2pwqqjnzd.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcxdbdjq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gt2udvhuehl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2wpxjwthg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2donxwruo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2kzijxzmh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnpixmc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2fkwsoiuz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2cdibkytw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2xkhhsupr.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2xepeyjqz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2onjfdemk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqroburj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2mwajieab.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2rtpadnxa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqdrihst.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyayvylu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gt2dvppnlue.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2vbgjhllf.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2tjhvzdwg.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2szftayyq.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gt2ornoprns.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqfjayvh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2mraqybrg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2byebccpt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gt2pnuzdixh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gt2eltjqabo.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2nmnxtsir.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gt2azacrmcd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2ulkwdxaq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gt2hqslaoom.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2sghjkyhh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypjygbzw.html


<!-- 参考信息 -->