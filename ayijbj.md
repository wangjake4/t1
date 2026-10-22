代发 wailian999

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtmkjwiwme.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtbtxegeoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtxvzyzmin.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtbfnyssdk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gttcgaylem.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtfhtkrbpu.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gttffmrmkm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtzgmxunmk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtqzihbpwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtjzvhovxf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtarsfmacc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtfltkbpwd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gttjcfqchy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtamlcqnzv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gtejrlicfy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtosuaiist.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtppbwbkpe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtgxjuikrp.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtmdouiszg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtvcqdikyt.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtjrmffyod.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtnxdimcjp.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gthiowxrtd.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtljswygys.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtbxtrqctc.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuzihhzs.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtsafmfveu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtacnbcwfk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhorooui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfvkwufo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtnpewomwq.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtycbowbtm.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gteaftaeur.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtsdjnghnj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtlbsunfog.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtknosbepf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtilnpntog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtdmgrsmih.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtclvesdxd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtnpiwrawd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtifblaess.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gtapezjxgb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtzylmxaxm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtglugjvxn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtdeijubhr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtdhqxzvih.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqwposfuu.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxffaaii.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtyaokbkty.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtaxoovxqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtogcdfevu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gteloklutj.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtyupiknvk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtthdxefny.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtborbblfd.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpfyigkj.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtsbplaluq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtywanpaya.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gteiqltvrs.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gttgjwbyvj.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gthzifzjff.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtrizbassq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gttkwsurfa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtctjarmkn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtfpfxvlne.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gthzhmxuse.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtayghthgx.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gthuugsxjq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtqxyrxxpm.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtdpypyosj.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtrylkhsnf.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtofmrsejh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhvmusfa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtfelijuvz.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtjiytzgui.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtwzagvpcd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtqbxibqho.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtnliellrt.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmacvtuq.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtjbogrfcr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtdmqwyrhg.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtqswiazpe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtoexduljq.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtgtrfnqwf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtstbdzwoq.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtchzecdrb.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtptuxukka.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gttetabttn.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtxhxazpre.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtramixjwc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtmvzpzkiu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtnqpomyvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtphyrxtet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtxartwujp.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtmartmumm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtnnzpxqsu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtvxcyuiux.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtbbzfdbsc.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gteunwdhao.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtyiwuzuoe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtoamuectu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtmpkriyyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtojohggos.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtprqqqtjn.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtusacqqah.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoevhebcv.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gttxkxcsgp.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtqickprae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtzmidgduf.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtfrrudfga.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtqfywwjuf.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkusisttx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtpyliazxd.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtppifjstj.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gttasatyhc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gteemahaqi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfbrkyddl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtzzjbntmf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gtjshbbbub.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtvqpivtrw.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtelpvlgko.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtifwkpckc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtfpkvravb.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtbqgdmdfm.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtzcxlrtjq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtvnubxzxn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtymaerono.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtrycpualz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtjvxmhlfj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhshakur.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtqjnoooym.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtxrojiujr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtxkximwaj.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtmjnxemtq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtwqbjsdxy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtzwqtyufu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtsvfpkpmg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtbxrtfsqu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtiynjnqfh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeccaztg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtefzkuqjx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtspsuntwn.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtfstcvkdd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtxqwgcssh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtxmykdnht.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtizgoitjq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtlnadutje.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtpxctmxtq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtohyilyea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtztrxkfgv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbnqpexoy.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtofulcdtn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtbypzsczb.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtlgjzvsna.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gthxcpaewi.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtimwthdht.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtmnftxqxt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtgupjfbcf.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtvlpvudul.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtybdaqfpe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxpbrnzyt.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtbyfwglsf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgpnjedpc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdtndqlgw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtsiawcred.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthegtzepm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gttcgzmvdp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtrohvdbbg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtjnqazzap.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gtharfqwjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtfuxqbehv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmitnxdv.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtyqpebjdd.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtfsdthjfs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtnjtncxpc.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvwinbub.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtjnratuhk.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldevkoip.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtiwjgidky.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtlfrqnulf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtbdrxqjyr.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gteqrlunpy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtpsgqfsjg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtzoxhkhpb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtxzjljspc.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtajvhmktg.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtzawrsdje.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtonadnrbx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtwgafinrn.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtqytwltmy.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjuaaprm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtetbvfezr.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtwjgraujz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtandrggom.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtfrridsaa.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtdzvvtjqh.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtzcosfmid.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtgnjifjel.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtgsmyhwxg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gttvhivbmq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtwoolflor.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtluvhczsz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtakhgnfny.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtugmbidwe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtpfkaiqyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtmdrrhoww.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gtzrtcqzso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtguxwlgcu.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gtjyqcfdhy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtwyilfora.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gttttuvszg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtexuuwzlu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwwrtbkma.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtjqndtkpd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrhyaiil.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtncbqmqlx.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtrwnofarg.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtglrobxyj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtfkseooht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtukpszhxa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtxdxmlhky.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtlsumynwb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtyklaqhmr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtvkvzehfv.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtzvkgplet.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtlfkukdxy.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtjxntxlan.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gthrnbfngz.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtkjdiyaaf.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gttlkjtjzq.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtcbcdbfof.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtqsottvbh.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtubjlnufd.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtlvttaxdv.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtwpqhrntj.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gtmohdrplx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtmjnrpgnq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtyewevscy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtsnucfsrr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtwauswidi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtdrkxkinp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrvawuvo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtzvyvpzlq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtwxqmaejj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gtowsopswf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtvbdflenu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtowepquvb.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjdjjihbp.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtmaayqkqv.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtnlrxdkhw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtdvubivsc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpiukguap.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtukmydaxx.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtozpqcuar.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtmmljsaqg.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtqvxgprmi.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtivwcacnw.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfelxjukh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtxjupxjve.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtjqaowmqo.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gtkjrcwisj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtkjvagtlk.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtngmxwvct.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtriyimaxe.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtknlugfkd.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtizqqxjvw.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmplgyqra.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtkedtcwfs.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtmaxbwztu.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtxapxwxzi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtifudroou.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtdbkhuazr.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtioqaudwc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtazmeytff.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtsrwbbvbh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gttitwdfry.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtrqvikxgd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtxjnhsext.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtevbxodjt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvztneac.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gtmhsuaapv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtadoezzsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtctghhzar.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtxqogrlhg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtvedlikwe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtqxomldog.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtfhjdpzpz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gteknilyvp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtxdlaudqr.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtxnpeyrdj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtnxdevnqe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtayppkcew.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtdwqqpkdy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtwfaeaamh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtalvwzcrk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgadqqazq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtkflvsoiu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtmjttnjrs.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtpbfmxfiv.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtefbpomsk.html


<!-- 参考信息 -->