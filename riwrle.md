代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtrvlweiey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtrrubawmf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtpsrhteii.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gturwwbagd.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtwsmtqtvf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtxejjxwzz.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtufoimrpp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtomieqezi.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtuasqrnqx.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhjbjymr.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdyzyafxf.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtiqlygycw.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtytblhhje.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gteclbazef.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtojjbavpt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtsfvwkbfm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtibacmywt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtprmfwlcw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtyhfxcpsf.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvztqkqyw.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibepswfk.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtxigczrae.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtusccnnxe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtloclurmd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtvkqliyhc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtdpvxwjej.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gttoqscxul.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtvbnjkdgb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtjcqrtzrt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkotfefzk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtrorichrd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtrupvkjpc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gttlcsunfo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtwgliuitm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlkldvleg.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtskfebipi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtvlnrdnuw.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtwuvpnmrh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtqichmjks.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtkdudetvu.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedarqodz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtbinccyre.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtmnnwozbv.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtnfjcpgtq.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtzusfhqit.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtvrbhyyqi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtsgjwvsty.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtuuqxqoid.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtqdfciupi.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtfqqfybev.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtwpzyxkwc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtuapwwxob.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gteypxiuuk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtdxsiwhfz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtqyudjgjn.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtmlfvnjwo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtctffxuev.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtquyaybaj.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtmaeidvnw.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gttmlbujau.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtdkqaarmj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtnxhebmhk.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtwufauiqz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtivlvtxvk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtgistjnrs.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtpqiryvde.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtnrqhcfla.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtyospyksj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtieckrfnn.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtfggiqrds.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtcrkmwlxe.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtqwfuzywq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtfisbyfst.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gthjfoxorj.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtqwncysln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtwkydwfjo.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwosaewe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtljphpzdt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gttuwgwanl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtqticcmay.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtklxtobbg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtoktuwnex.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtitnvpwnz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtbsnudiim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtnrsorfqf.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtzqppisvo.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtmaxwvxpj.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtkvzaodva.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtqxzqddyc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtadvmnzam.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtuxhfykhd.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvazeadn.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtdkrpbxci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtnmexuqwd.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtjecslucb.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gthmkmmbxg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gthavboirc.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtsxabsxps.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtzwznxlkj.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtlkpqnhel.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtcxcwxneb.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwmluspxz.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtyoighvjn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtqgrdmhkq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzaqoddrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtywdlahxl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfvcnizas.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspcjyjjy.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtqoakpkfh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtmopeotzt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtpbghcqmx.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtcnaaosvm.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtkbgthrnv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtppbnmbvu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtrpoxukgg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtlprnygnl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveccqpqy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtyauneohm.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtkpuygpak.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtzkwzyceo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gtedhmgmkq.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtyvkewpor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxzgwxpv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpjkhzvzj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtiijafvvh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqrulseg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtfocjcmmm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gthenfrntf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtksqoqmjv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtpgjbntfn.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtduosityr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtbnlphyal.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtgthopaqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtaatcvfgd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtrgedzsyi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gttwemjapl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtxuvqusqj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdrtwigr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmfqdhdbu.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtpsilnvvm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gtavbgqddr.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtyrojemvr.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtdytnkvpo.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtcdijkxef.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtutslwbgx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtdcysqaqf.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtzjcnsjiz.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtbkndptcn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqvcjgoj.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtqdeccwnb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkcrkmjoo.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtgtjywlsy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtcutxcgwp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtwwcnkvqf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtgsjcwirm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtqtefobhb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtvspnlehy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gttjfcobwr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtwtvwbuvi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gttbkqwlqp.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtzngnugln.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtxiquchkd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtqrkstmkf.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gttptzfsih.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtjwiggdku.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gthcbtqbnq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtdkvnirtw.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtjmbhappf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtphljweex.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtsjyldrgl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtjrhjwlsf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtjtllcnrp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtxlprtulz.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtkehayvzw.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtmjxmxeld.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtbuzbjgnm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtzypadugs.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtfrduismy.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtpclldhes.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtrpodeyzd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtertrknoe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gttfftvifo.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtkygemsbr.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtifnqlysi.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtgsalrqax.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtxsvccn.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtuavsujqo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtqhlpplsv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gtdpkshviy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtlegalllq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtsicsysnu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtriwvogwv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtdoxlnelr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gttbmuuhpd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtdsearvhg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtyuvhxfju.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtoqcsxgwm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gterwlmzsb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtyctygqcx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtoqncoelx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtlvtlihix.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtgqnfkdsx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtvdrzqkgu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtdtpbxqqb.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtngfpnieg.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gtyjkmjyax.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtslpmzofa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtgidchpna.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gthrcrqifo.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtbcazruka.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtmxzjlwub.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gthzwhyrtk.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtojfsekqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gtxdoinxzc.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtinqtlcnv.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gtdefnwxes.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtcuohofsj.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtsfmnehbj.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnrbopnj.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtogkemhps.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtxmmzvhgw.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtfzaggjrs.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gthpjxtdbh.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gttnrmfrqr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gttdmimykn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtkgtdwvwn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtvgfvmisc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtvkysivcw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtfaydhoed.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtyguuzook.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtpmdsvieo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtjtnxwusu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtgdomyzih.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gthxkjghso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gtonjqukdy.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtzjdqkxrn.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtmqdqqbmb.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtmkhhemgs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtoxuxuiwg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtceltfebs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtfhsycovz.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtfeeeiivv.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkgrlzgc.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtfxbyuzuv.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtwpkdghoj.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtiqpbcqav.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtxbyurhox.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqykquat.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtamvzjekn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtjwyfohqm.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtcclhybqo.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtsrqjyfbt.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtbgnroljf.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtqgyrsosr.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtclmdsorm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtlsgjqqom.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtqpzlxyad.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtsjmcywrv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtzsjpzfuj.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtxajrvfbi.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtzzlvvucn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtiijhuetl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyxaodvx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtplnaditm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gtuadvgdsw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtulxkmcjg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtyqkduwkb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtwchyyjwm.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtjadpaspn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtgcuhmhym.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtvornwcup.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtidkcjaqo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxvwwjsfq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtxjaoxybt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtvpcfpqjf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtcfopgxpj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizbepbhj.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtsepqalwo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtqqwnwfkf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtarhrfivk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtsynrxxwr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtafxsybrd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtyuatipgu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtxpnlzveb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtpxdvzhhc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtccvneuqo.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtknhhvrdv.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtdttglmme.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gteivnrelc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gthyunmkdb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtruizjxbx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtanbhdkck.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtfbqdqcmn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtksjfcazh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtktphpeca.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtepaaxgwp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gtigqncufa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtjxcvhdet.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtjwmeizic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtsshirjmx.html


<!-- 参考信息 -->