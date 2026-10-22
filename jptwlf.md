代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2wpdwwyqq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2uetbudnt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2jigjrywc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2pbektcnl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtevozaf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2fyonjnwb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sljxtitz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2tmgfzzrk.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gt2urwytfck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gt2svhmpvmp.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2zpcayhgn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gt2xyqsqgln.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gt2jvldepvu.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gt2bubtwkxf.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2uqkybxkj.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2tdrezlvd.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2pnvsuvmm.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2pzfvrlrn.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orosyzqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbudcjby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2guilbwpd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tolofjua.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gt2aycfzqds.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ytxsvcjq.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gt2ujjrxvet.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gt2mbjpkbgc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2wkrucbnp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2bwjaduye.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gt2tnhkgpil.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2eerbomaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2jugbmrnn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gt2phaauhlr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gt2jyfyfhju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gt2vsdlcgpm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzdupjaf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2qdyavwln.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2uydprwft.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2inuvlmqb.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2xnduigkz.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2kmllwjsx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gt2zvgoneoy.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxzoaoql.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2gutjnkku.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gt2ypaotggp.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgxrmloy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2yrnzsajm.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zowezbuk.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2bpatyfqv.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2ivimkuoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gt2mmbhvuys.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gt2qgnfxfht.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2ryjkurrr.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2smpxibss.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gt2lrhxbjsi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbdufdtc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqjnfikt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2younvvpm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2adjigzvc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2tqbwscfs.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2nkfgndvc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2knsbvcpb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nohudqko.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2xntpyfme.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vmjcosaj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2xzexcihj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2zquokagv.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2tdraqgwt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gt2stdyctcc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2xhdiyigk.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2xfakyrav.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gt2hzhgmkna.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gt2wbetzxey.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2vqyosguo.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsllflsq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdqjsoht.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2tlejgnuq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cftfymbw.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2pompvjcr.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gt2pddqyrps.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ymiuxjvs.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gt2tayaezuo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gt2ecgumjqj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2fijfvcir.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqbtdnmc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2xyocyxua.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gt2aqqvuvug.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2mbtaypad.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2ngczrrlf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2mdgdjebr.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gt2uohlqrlj.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2hfoayqyy.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2yybtuynt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2hahdylbt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2sviihaue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gt2zescmfho.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkumgalv.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gt2psbhjsvp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gt2grnrsfae.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2qobcoepa.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2kadlepci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2nbjysmof.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wggowunc.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtxgrfwk.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2wppfjnxl.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2ulvevzjz.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2lgegzidy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiqsyfw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2odqmfaqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2uxdsjbvh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2mriwcgeb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2gnjetcre.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2ykjpqsht.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2eyjwuhjj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qceahcyu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2hpbohzyi.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrzesghs.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gt2wemtdbfl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2tnvpjhrk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2wizdikwa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2sfjhiusw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2nbsflqln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2sccdifqd.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2cpwswkms.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gt2jfhtnhnb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2kpoutuse.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teebxzsg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2ymxjtsuu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2pzhzoait.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gt2yuuexyqy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2jhkxnequ.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2ggrcvtci.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2riuwwhoy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gt2ucezklrl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2hymxhqbb.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2opzopvvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2zqquxpvk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gt2zayokcul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2qndnrpip.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2kfryeize.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2wkfbguie.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxzmocpj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2odsdapwf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2fxefnaof.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2xobvoqen.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwmojbns.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2muacrxvp.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2gzwwnhpd.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2iefmmvjk.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2blhfqnjb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvydyxnu.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2xwhgobpj.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2nlfpyvcp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2taqglogu.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2hfhvtgic.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2slrlqert.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2dghfvozj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2pfongsxk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gt2redwcqod.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2njqnjojj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2uaazxirm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gt2nqsnjavx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2dvfhbdip.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2iokyxgej.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2wzlqkiac.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nejyiqxk.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2vyucavki.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2bzcvqjbn.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2cbrkfzse.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2jqibkyyy.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2bjcltltf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2ftimqhxz.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2jhwejcnq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gt2fjntlnmq.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2xejuiwru.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gt2vzpeusow.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2sfhmohss.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2lalxjlzm.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2vphcbfbd.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2thbnvmvo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2ztalpsct.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2mecssumj.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gt2vzjsvkfr.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gt2thnjgjiq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2lezxupff.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2qjxqjngy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2nwvsxgbh.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2hqrtsoxs.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2rmsqavba.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2wjawegdr.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2xewdbios.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2eqqkilrb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2hrjmxucg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2onhmmifp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2lvhupyap.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2phwyqxnt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2hihhulzi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2vawlqnyh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2dytdmfkx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gt2latepdle.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2htgkuotc.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2ppdqzvwc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2hmovibhq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2kzknrqmc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2xtewarue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2bgghadqp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2geujubij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2nlilvadm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2djtulzpc.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2ucxpwyei.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gt2hbbqnocj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gt2gfksgnqx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2wzoudhcq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2tcsyaoly.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gt2jbzgyyng.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gt2zxmazqmj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gt2lejirhhp.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gt2hngbnkoj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gt2tirhdwmr.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqrxbjll.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2prqwgtsn.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gt2vwrzcolf.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ichkmrdu.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2hgmvpwds.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2vhtkxvpj.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2vqvaiyvm.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2vtjwrhdd.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2bhlcnqnx.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2qnbvvcbu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gt2zydomwoy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2sopctjfl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2xghlnexs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2jejlhoiy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzadrmjq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2mqyewlwa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2tgwtcnrh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2wxxnljvx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gt2mzmztcvt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2kareqgay.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkksaiyv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2ijkdvnzu.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2zoafbnqz.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2dkvckycq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jadhjokz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utdzoixv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2zdqemeyv.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2xallftwz.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2tfbniwhv.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2fvkrcjzv.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2wtgkzuxz.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbmkltlo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2zdlcjmzz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2susxwqkb.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2saqvzmtp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxlvlzpi.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gt2kaelxqdv.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2syfgezzc.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2lkkndiqv.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2jocofagg.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2bckcijon.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2yfvnpomu.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2olgzhngv.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2fgkhwiuq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gt2lxomooqq.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2hgugzbin.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2lwsxjyei.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hapelgmx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2jhrjufwh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2uvjnikel.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gt2bgpzbxif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gt2xpvalvsp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gt2rcsjxpmj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2bgacpcym.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gt2fvgyhljy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2dptdgsmj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2ldmzyrxt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2kllgewdx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2xvhcgbkh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2nnglgpvu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2maspiraa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2pyhobtqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2lypibjcm.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kacnyccy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gt2oppirsll.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gt2hmgctsfs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2ieiqlchf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2vgijpcvk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2auqduebm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oiunjktz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2zmlnmfdj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tzwlagtp.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2ffpzlkcf.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2dkdxskgr.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2juchjqqk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2ltleczoc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2wzhkrkut.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gt2ejjpqmne.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2ybswhkgl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gt2xpmloril.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2zjusmiiy.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2eaqreibr.html


<!-- 参考信息 -->