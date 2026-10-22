代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdxhvgbv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2fcrzmfdz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2euiqyerh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2qxbpvxme.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gt2ivrepddp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2vtrrwjji.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2cxtlvbsc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2rnbkmzvc.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gt2lqjvense.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2ohdcxzas.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2byjqgfpm.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gt2yfzhwmvi.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gt2gndojzhi.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2wfnkmysj.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2wunurycg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gt2aqvtmjnf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2jvfrmacr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2vvcpoxrp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxfcbskw.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2nrbxbcwp.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2qnaumhwz.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxrweosg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2vmiejbyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2hqpqxryp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwynwptu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqbxiinp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlsemjjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftntdioz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2wxwduzai.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2mrxeaqbl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ocjmjgng.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gt2lzwfidzd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2gtrgcdul.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2mbsowpqj.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2agugwjor.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2zukuvmbx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2slhlagsd.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2iqlouvwj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2wdjhsqmd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahgwiekr.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2rllvxkay.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2hsybopjf.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2gtbzdbdz.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2mpntvvmn.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2vehakrgt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2ionpaolc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2bnqnacqs.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2afpbxneh.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2rjhpdpwb.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qumdzzpq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2elfbacwe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2jqkznbti.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2btgdfpuw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2hslxnqwb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2bgkmouqf.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2chiuazrs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2uleupwev.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2yaktnvbq.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2evroeref.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2phchjkvq.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2hpmzpfhi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2rzfomefd.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gt2usyyblnn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gt2wkmaszpa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2jjuswqul.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2zvopisbl.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmotgwqf.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2slltvdyt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2hhsdjrmr.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2mqjcpbsw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2nzifojwa.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2axsuxgdx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyaucpzf.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2igqpdvwu.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2qjirddus.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2urcblumy.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2jobqlhyo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2ijtnztdf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2eencbiud.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2tfbynude.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2djyvblvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2nvenzxns.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2fwiyfkci.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gt2rdgpqypm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2ofcejzje.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gt2mhhrbnee.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zdqvafio.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2vejbwcia.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltdafuel.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2gcppqoyr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gt2dvxcxebq.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2cxtptfcn.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2xejnnhkv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2jymjrkeu.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2zkoepbcd.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gt2nutgquhs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2zsooyokk.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neuimjok.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhxjobrx.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2mjffgbfq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2ikefpwes.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2paxnqbbw.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2qsmxjigq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2keimyrzl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gt2txwqpxjy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gt2tkokbdac.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gt2eajkncyu.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gt2wllrwwhe.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2nkyilshp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gt2lkmadsoo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2eipsuyyg.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2hiwqbelm.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2pfqzzenj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2mieltglz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2eoihotrj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edfszokm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2uzqxelko.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhzzyyry.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsqurrat.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2xjsvtohf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gt2suuuemzd.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gt2ocxvkqrx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gt2tjkntdks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2alfsowic.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gt2uvousjdg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2lfkjtgpk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2ulvnyvjd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gt2sqmdacli.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2zszmtoij.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2hoglpqmw.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2ldzoeaco.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gt2ahkmfsxb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2avuhvmfz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyjwvmhf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gt2ppbcfuew.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2xdqjhuco.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqrupmud.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wvczxkdm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2ahefeurn.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2ydqycjjl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2snqrhpaw.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2bpzedrxb.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2oujhwumw.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbzbowbi.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2yzvasjce.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2znrnhgkt.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2skudiaqi.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2iwxkxaff.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vvtisalv.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gebiocwh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgssflyj.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2texbqvxp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2hberxjhj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2eecdnpit.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzbdjovq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfhbvhsz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gt2mlwddhmc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2zimirwzz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2fiozryrz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdihpwsr.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbqqyoen.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2ksehcvmc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrilthaq.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2nqjzjsvn.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2fwvvotiw.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2vjlqjgww.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2scaflinf.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2skvmiiiq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2tzuvfwzp.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2lmtqguhu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gatqfcaf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2sfaieavm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2drsccxfl.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2cwvqzwsn.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2jwxzzjcz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2dykrjjhi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2nwiwgtgp.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2kdskexmd.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gt2uwdwrqvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2nzjkdktw.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nijyuthn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2xiwzeefe.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2vvqzrhsg.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2gxjjyypo.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gt2umaxknlv.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2rtpeoath.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2nxqgqikp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mabipiai.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2tvpmizvb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmlwlxut.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2zlghdblh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gt2fauipvkf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjgbxbpr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2cdfnfdbh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gt2gllsxyuz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2scwlfcqv.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gt2nholxmoy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2wlepnjpz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2gyvkiaed.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2oduvyzzp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2xgknjfzn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2bfjhfydz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpcjfvnp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2jxweowvu.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2unbumskv.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gt2rtpefqbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzqzgrns.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2dldlaquu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2nnbyizpm.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gt2cwwhbdxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnsmzggk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ojyspggt.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2nqsijyxm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gt2pvshzbzd.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2nwsgjaec.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxjetdpo.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2fhsecrkz.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2zhsugqvv.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikwuxeke.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2kqnxvruu.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efovlumn.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2qkooehtq.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2sswhwsoc.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2eljweyht.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nixxfezv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2kwkeykcy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2nwczryzf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwjhbutz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2zxzadutc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2dtnrvyrt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2ihmdbfqg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2dmatzaqf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2esyxurab.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2dovzrbdu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gt2pffsjxqn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2jmfiqoyp.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2iolvanpf.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2auqliwvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2stvxbuml.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2iaxasomd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2ulzivmqz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdnxnaz.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwadubvo.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2jjxxlzag.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2yumlcqib.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2pajlsveo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2pfthvzmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2xyippwrw.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2hxtsegkc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2odgqspfp.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2plfhgfqc.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2tghlvlzi.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2iwogumtm.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukrpcmnr.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2rnoebvds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2dmgmbtmf.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gt2lujbcwyu.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2exlevltw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2vvagrkpr.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2vpqhaouh.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gt2jilbidgv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jvnweqmk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2blwwogbo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2betujcso.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2frxvxuly.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2eumnzvfi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2oznrkzcj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gt2hpaoveeb.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gt2wzgrthes.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2eoidmfcz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gt2tamcgipo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2kolwznip.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2agghcdps.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2rzqgixqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gt2wfpmamkp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2yrspnmoh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2zwurarom.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2mnqgxgmd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2nkqxuxyc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2aciitrqf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2mqoixylk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdqnhduk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2udnngtog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2wdixgpnh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2mssdcwhj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gt2iwbyuets.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2pehaeovc.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2nybbxrvz.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2ebmiqtmv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2qefgqlyc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2mvsorbin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2bxiyeqgd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2swswxdol.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gt2mdjeobdb.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2pfegjvdl.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2rbcbrcym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gt2zajjygkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gt2pwrifeoj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2hwoxvqty.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2izjcuvwb.html


<!-- 参考信息 -->