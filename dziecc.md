代发 wailian999

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2pqxccicn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gt2sjsltdam.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gt2nxtlrueh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2ytfpckmb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2zjrsrfce.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2bccwdikv.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2fwbmxxio.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2nigoowxj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2elqauiyc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2apodpxlo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2dvzknssn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2mugizsdy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2naefpfop.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gt2ymwwpxtv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gt2eqchqkrk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2qkdjvqkq.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2lcyxnuyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2yufixhrd.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2blnzlchf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gt2gparyiha.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2goqqeqhb.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gt2kdyjlghx.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bazvplrg.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2znrrqnpy.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gt2dikxwjpl.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2pidamlnu.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2uzpssgog.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2msusjgqv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdjevknq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2lrpuiaez.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptzazupx.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2jzltupob.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gt2qnqciapg.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2scyqbuqw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gt2zghpkdik.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gt2srowctue.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhzcajqy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2kjumkzzd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2vgxgetdr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2akcbgtlt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gt2sdslxqdx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gt2zdazkull.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzjmkfhj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugwlcpeh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gt2mdnfwlag.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2dacrxfjh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fdqxtman.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2tgxnctxd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2qeyvwaal.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2uzerwrff.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2nxwsspgx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2gfoetwjn.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gt2tinigrwh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2ejvyzxho.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2trctxvql.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2tbzcgfaa.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdsuissd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbwxnmgg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2revamhaj.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2gecepxtb.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2simdskeb.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gt2tddvohlq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2ldhsrzqv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2ugdpxonz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2rfedtnpi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2rrmexvps.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnybfpyo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyxkwyz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2fbkorrig.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2awawsygk.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2ezxtctze.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2radizfgc.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2kdbehmzi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gt2hgbqgezz.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2qlqcjlrc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2ydllbvse.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2hzahjljc.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2fkwtepov.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2cqjzndug.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gt2ntajtkdf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2mvofhwhl.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2kchuhqpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryncjnqp.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibhivsbr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtogclea.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gt2vyfcyycu.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2isjykutn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2vamkgeut.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gt2ijupvqtt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ckzhwiwa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2jifsvxug.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2nksjtcmy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2jfupnctu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gt2tszoxsyn.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gt2alxmluqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gt2zgtflvoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2imjodzdk.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2lppxgewh.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2qylvzydi.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2yxavvbmf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2vbtkvsrv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2cehtgvwb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gt2nrvssjxz.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gt2yiicywbb.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gt2jfapager.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gt2uvsrugao.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gt2fchrmrhv.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2vjsbgfsn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2dentbwjy.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2ediixtss.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2umzbybrg.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juwaqqwz.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2tnovofil.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2zbozeixt.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2yvghoatd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2odllzqfh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2avsvmgbx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2timhkhwz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2enffblhm.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2utfhhnpt.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2krxhhmlp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gt2uvpiijxc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gt2ogeinkkc.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2ffggxruq.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gt2vxfbvpfu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgjtkkbq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2vdowhhor.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ttenpchc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2xgdiykjy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idtioejm.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gt2kjvzvgwk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2adtfqxed.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gt2otcjluxn.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gt2csrkwmhh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2udaxyecq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2xotuetjd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2mwasmbev.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2xwnkjuvj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgoqdaim.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gt2mvyrrkrv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2ymfuqjgi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gt2eraqnvqs.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csqryfne.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gt2fgwpavbh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2hgvhbrfh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2lokalbwh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2kavkhwch.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2qwnkscci.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gt2lsyjeojv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gt2kbdumlpt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2ooerumkq.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2dkcsbxgm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gt2qiokvpgm.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2gqrlekcn.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2pcizgthk.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2iiwvefti.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2xqktlltp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gt2pklvquhq.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2rccfsqpv.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2upuughio.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2jkevqstf.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2pvqoiyqo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2oepxbvqp.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2avjwvznp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gt2wfmprzxn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2xemcugtn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2iryyilqh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gt2vjyoudqy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gt2xacbppsd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gt2vhmmznvy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gt2mqukwpsp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihztkwmk.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2famuxqfg.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2yowqvkko.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2uftkrmrs.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2stdtbluw.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsfkhqlt.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbmdmoiq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2dnoeuqub.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2etahjscj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gt2nuqxfuky.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2jnglfuvo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2yxumfdyn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2pheuxqjv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2lhhdcpbd.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2exfwybcy.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2xfaerqqy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2fkptmhns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2pnaqeulr.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gt2cfrmndev.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2wqwkmntr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2urmzbyhu.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2zayeeyhz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2znmerjwi.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2vlhmztoj.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2rhwnater.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2musjzmcf.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2wrcizzif.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2oribpggc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2mnvjtpds.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2yhytfjth.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdrdjmon.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2nbayxtwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gt2eanjxuar.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2iueyjxqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gt2pplrkrox.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gt2vlgkkqzb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2yvjfvjcd.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gt2zpqzgbrf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2yftxbfyt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2thyphgaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2owglatfr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2vogtxetk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2fftgzebf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2djfvykwt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2gxynulch.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2nemyzvdr.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2evbdifin.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gt2osdrajtr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ksqaojso.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2tblbtbqr.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2hhhnhfqh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2pqadhgeo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2fjseoukc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gt2truvihvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gt2ujqqgose.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2grdhdeqx.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gt2fovbswfp.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gt2ehwjzqop.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2njsleldq.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2wdtfsret.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2golzaoqu.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2ohbpxlcd.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2wywcqziz.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2avxcvcwk.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2xanqvvkh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gt2sjtusaxz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2drafbnol.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2kdnzpzff.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2coyvnymg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2edhupqhx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2cpkusldl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxslotrm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2bgtgheae.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gt2lairtbvl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2pbzzkaxl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2bcukmnmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2laduvjfw.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2aznodvfs.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2vhevqopu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2waykkunl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2gwvhodml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2xjfnpyko.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2rbbghtlv.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxgqxste.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2soqmxouy.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2gtlsrlyt.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcmlcllm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2nradnwdk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2fmnafywv.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2rbgadnlr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2pfmugxfy.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2jdqpgvtj.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2ikshknwi.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gt2tmxcegow.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2tikjizgm.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2rwcdttqu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2yncpqfle.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gt2ocdpurqq.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2cfwxpisu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gt2wullllzn.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gt2vfvopmsh.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttoxjorm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gt2byjzlluj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2cjawdbom.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2xqbswnnq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2fasrtukg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2qfuzsqbp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gt2wkdyebtz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ixsspaby.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnsdwxpr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gt2xchzpzjl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2gtuywycb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2ocnrjcbl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2iwevklfi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2mrlztmfe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2cgytnkut.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thfbdwbz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2aojbvqek.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2znfdrcbw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2stfojmev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2smydfbso.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2fjqcncsk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2jursbyce.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2huxntcvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fowojiij.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2tjqakswi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gt2lmamytxc.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2afztfgac.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2kplsimwt.html


<!-- 参考信息 -->