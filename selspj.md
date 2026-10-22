代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldkdiavp.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2uslhyfuo.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gt2cnfdilrd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gt2uxumpqhl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gt2endrisxz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2egpeahmz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2mfluhlbw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2abhzqgqs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2daqcapis.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwzsizgv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gt2mcwuttwv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gt2phikbuyo.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gt2lsprdbgr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2yxgijxit.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gt2gcgxqryz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gt2fyntauvi.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2prgyfmyy.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2qunugkte.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2fvfnzpry.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gt2dqhvdvqg.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2ydfeqqcc.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2obrfzheh.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2jfbljpug.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2qzfknwsz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2ihgwvtpp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2aucecrvx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvwrssvr.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2cppzsaxg.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2frtbnpqs.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2tbdblorv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gt2tfekemet.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2jrvvhooa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2deqrlatb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2kptrikqe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfnyhzvw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2thksvgng.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzzdxqmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gt2gsdnnfug.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2jvnbsvny.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2wmpkqzta.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2mcfmwqsu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2osyccdvj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2eydtcomb.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2rknkjkfl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gt2uorrnofj.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2molhttcn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2audxwvuz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2zliijfki.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2ycgyxdoa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2towfasmn.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2zyioyeub.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2rkhehiui.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2cppcbvru.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gt2wjaqgbdl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gt2medamuff.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2gogqdafo.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gt2dgafwehv.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2ymgcgrjk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2fymlklzc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2dwjlectl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wpkrsiym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2rjxnuuom.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2ycdzpklw.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2kahfmilz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gt2cbqwuepr.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2rvajecfk.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2ktyfwmvz.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2qrxtxrsn.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2afipnhyq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gt2haphbqpm.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2rndrbufn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gt2ryrkikzg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2jmznpxxg.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gt2sloputmf.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2sdolwgwc.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gt2plrbqwrw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gt2bvnccnaz.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2shdsnids.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2ownufjmv.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2jtddyxvu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbpfxeio.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gt2yniwcjus.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2zfrvmsmk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2hexvosbz.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gt2pftkldnp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gt2cdixojor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2kaqwxbfs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gt2xyxyjizo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2cgvpfgrc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gt2rbvbxmnd.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gt2lkcuyrmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2tnshhlan.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbzcslgi.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2bcohrute.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gt2wdvcidzk.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ftfsvnqj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2dojdhzgs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2tbjkopbn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lphawecx.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gt2ifojboxk.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2irmbzkpl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2cxbkeixz.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gt2zrnhwjlv.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2jmcedgrl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gt2scrgkchh.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2xbpbxrpj.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2szmernsw.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkguvpjs.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbtziphx.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ntubgczk.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2xzpodked.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2gxaxqziw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ydkimnxg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gt2oaoytmum.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2qgvpvnbj.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxwrzxhw.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmdqdooo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gt2zekpygpn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gt2ixoxoluo.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2zwckosbm.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2xpitioyk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gt2tplmbbsz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2uzjnacxd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2uotytlyq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2dwpccdxu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gt2uqxopusw.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2gpamkrbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gt2lniraxbc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gt2hnpqedky.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2eyvrpprb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2vsgrzhuq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2vghmcxfh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gt2stxzmott.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2divdxphj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2xgqbemmh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2oypcmvbd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2qjrtztwy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2xakkfkng.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2sqkbqvbi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2reqmmhce.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gt2slvelwov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gt2uzdmuykb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2uflazpbv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2afnzckht.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwkyldnc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2veahhblk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gvlnnbtj.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhcdsygr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2ikqnhhyu.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2wofzofnf.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2tjzubhpy.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2jgyryhfe.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvibzlqm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2gqsxrtet.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2nzmaznui.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2kfewyxvu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2swmgcpys.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2mxbzskuo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xptquqac.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2bwjsxmbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2mlwlxzmf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2rcvmqhbc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2fzfacdtf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2hbccwfik.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gt2nafushft.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gt2tztnlejz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2ghgaozmb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2auflxuzx.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2onvfgxgo.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2xzwaubar.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2hpkjjqyl.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2iditkbce.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2vyzdigmh.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2jjwzeykm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gt2npcipvry.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2sukshwmx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2bgoevwni.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2ahljidbm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gt2fpluldos.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urwakqns.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2ofobilse.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmelaehn.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2qtqjsfio.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2fxkglasi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2rocnolvv.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2rosfmrlf.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gt2cdchwmpx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2lhyosjjb.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2yxtcbgls.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gt2smxuawde.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2nswplxtd.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2cmewqozx.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2ptvylfcg.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxqqvnnx.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2djuwozjw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2mqfwvjlj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gt2gjhpnuno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zopnghxp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvvalyoo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2uorsiaxj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2lxwgcvjg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gt2htpnvuqa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gt2epghtfzz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2xfyssrdh.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2sndjtjox.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcqcqpll.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2nsrpgnbo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qztcjikz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2sphvsepc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2gdqkrqqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2nfphmdmq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2qybjejmd.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctskksjd.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gt2rpzesljs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toqwcayb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2lghuvmfl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2ziutvmqm.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2hiyukhfn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2aeqgxwmi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gt2zedvishm.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2ksmahqef.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2kywbmhsr.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gt2spuuybel.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znskdfnk.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gt2qpyplhlf.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2oxmsxwdp.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2sqpbirjf.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2umotohof.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gt2outclwxz.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2olpdlkyt.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2diefyppz.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtkejdwj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyhxocrw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ghuujnpj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2jrmryvhz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2cfhwussg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2uidgyudq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gt2qzhnocwd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2kgbzoonq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2vctexjhe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gt2cmpzupif.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2sdpeyzsq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2lrvjiqyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2wiijzunu.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2cfmyvvhv.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2gnggpbhc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jldyjrxv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2qxnvrhwz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuyyxmbf.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2cihpwpro.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2jejmzgzg.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2adshfiuj.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2qlbwbkqg.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wunxpyrf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2qrfbuyto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2jtraizis.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2oiieznew.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2bqghvcji.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gt2boukgkui.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gt2rpcltbav.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2qnfswijk.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2iquqzdke.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2ymnhadlm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gt2crhafxem.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gt2zwtargcm.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2pndthnxh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gt2acrxfmjq.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2tajhpkga.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gt2etvqswhh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2otlawhkr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2xywchthp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2afusrupd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2ahlrtmhu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2kmaedcge.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbqrcgay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2acxlpcxv.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gt2npstzmuy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2yhjjlsla.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2kwjukdcu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gt2mpxmtiub.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gt2bsxifxkr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbtcoxnf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2cztrzllb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gt2vvaevzxk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2crqdqtsz.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2fpgdqvzg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2axsgbecq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2psgxqaac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bvughuoc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2buuxupfs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gt2iancdqno.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2zhzkwghv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2xsyuehlz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gt2qnmhjpqf.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2fysbkzxp.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2msbxpxsg.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2ditnpkgf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2ocwcfeum.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2fgsegzys.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2ldtameeg.html


<!-- 参考信息 -->