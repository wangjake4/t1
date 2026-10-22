代发 wailian999

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gt2htexrtbr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gt2scfsuhzy.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2boyilldr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gt2mvbfpink.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2pelassxj.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldhxmjfe.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2wskuhtsf.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2fbncmssp.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2oehnfgxf.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gt2yzyhmkvr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhiyraji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gt2gbkldzrv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2olkuitwi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2wakbabft.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gt2uozzaqdz.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2laewtoop.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwskbshs.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gt2umcjxthm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2pcvkvzmf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2uzxjmnih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gt2qxoueonv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofhznygh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2trtryaqb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ipqqjxks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gt2rbrptwwv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gt2wzgkqhol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2qsddewzl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2vesnsgid.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gt2ckchsusk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2wymujeoj.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2qjclggxw.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2uhrwadye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2othstvut.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlckbsuh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2rccckpzd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2tzilyjdj.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2txexvrsl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwceqcck.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptpeggen.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2kkvxsgyz.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2nxaekeno.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovmphyuj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2kjhcjqzo.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gt2ekdqzlnw.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2gzcwcirj.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gt2fymnnwcw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcmjezpk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2pnvitpbd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2yrqipxrc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2bvnxiacs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gt2jijjdfau.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2wdasgikd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2csbeizvo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvumxszj.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gt2ocllgndl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yprruljb.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2miufywxv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gt2odwcopec.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2ffpswnry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdjdhnak.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2hpgnwgxv.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2plzvhjqs.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2xffqyulc.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2aozpquau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2yyfubyrg.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gt2wlhmvind.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gt2obclcemt.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2vhumhmfl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2yhxeootr.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2pjhuywvi.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2zkrycewi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2prqmnpzh.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2qfnvjfbj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gt2zqrdrtxg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2veghslcm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2hldanato.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gt2pbjcjljl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2xtfmozpv.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzqysbno.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gt2vumvikqn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2zjjpaahl.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2ptqfcdfm.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbdzgecs.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wiyvgtwh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2ddmcgvdi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2iemrowjr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gt2ezkkcwel.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2pwpfdbrf.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2tgvatxww.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gt2lwvhpnst.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2mqfmipjo.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2aerhkkdo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gt2cebqjmgt.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2biawvvnu.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2uymxiggs.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nefknxrx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2bzgugnmq.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2hkdyedlu.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2rptxswmw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gt2hevtbjhm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2bkrqgawp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2ykkpjgzg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gt2htijrumm.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gt2eonrdtsx.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gt2gkawjoni.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2usfneato.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2aghsdptt.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2uxnwwqtq.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2beriutkb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2wiswlwsn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwutriba.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xdofqitl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2bjuxxdyl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gt2podpoggt.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2indalope.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gt2araywgen.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2trirwoyd.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gt2ylbhipmg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gt2pvsozmxk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2qbfbnyer.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpwuaaux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2dqmcfywg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2xyyvneqe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2diyzulkn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2slqazskd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gt2aiagumhd.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gt2bfskuadm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gt2ouysytrq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2mafzlcrw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gt2xkflkuds.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gt2oztulccp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgqnivrf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilpgiitg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gt2tbfilzwo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gt2bhwatuwn.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2btzpxezc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2gnaceuox.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2silsethq.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2tsdomarr.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgvkthpe.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2jioxrxuc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbcqunoj.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2xompsdfr.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2mdrrmnkm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yefkcbjt.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2xhprvecv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2fixqdeqg.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2mepqeeho.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2ibrxyswl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gt2wugagyhh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2mjftcnet.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2smoscfgv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2psxjeekb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gt2bvdyfwbe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2pjfjdrva.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkrhyesw.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gt2jmnjhnpu.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2xnwjbobx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2qckrgggc.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqbuqtod.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tukaopst.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2oktxpyvi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2hwabvryo.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2qjrucxmt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fncrqwti.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2hlmsfuff.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnnsuiif.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2epdoqawo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtxousks.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2jblrqavl.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2jyjlzqpe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2texsrqwb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gt2iqtckowd.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrqxpuwm.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gt2wmvzsxce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2cjskrpac.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2ivaxxepn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2aalyiowu.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2raclakol.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2mbjyvmdf.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2pzgtpije.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2npuwusai.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2zetykqbp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2sjorkhnh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2gchqzizn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gt2sjvgnkzk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2huymmnhp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gt2ilxgsuho.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjqloofg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2mavzukdg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2igajpsxj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2latzrebu.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2xhdfflwe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2sdgttgsn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2wfhkdhie.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2svebhfoa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2bvzstfjb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2mjnmrhpu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2zymhiwlz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2yotigcih.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2muisqmxe.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2opwjlyln.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gt2iqwanndn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2xoczbzhd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2dztpikiy.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fthtlkkd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2ekufifat.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gt2fswbjnaw.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2iubhcxuq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gt2cgqylwfw.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gt2osfqwxpj.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gt2vvjwimvq.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2fadrppri.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2ejdzbpgp.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2zdhvexmk.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfaaaiwv.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2jkgudjkr.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2jfnwjbji.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2pdkghgya.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2mstnekgd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2plkgqgiz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2oswwcvzk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2scnpmtqa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2vkijhubg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2gswseiqt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2zpcvubiq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gt2bbqiogdw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2fkkcmqpq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2kzwrxazr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2kyakmzic.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbozftym.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2yohwfead.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2bfhdshiv.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2vmyisovu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2obocqrmg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2neotjwrf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2sszuwsfw.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2giplsrzo.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2dhmihskq.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2yfxiddic.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2ptlqxgdh.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnvzkdxv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2jxfzmaad.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2hwjgvoda.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2mznrahdo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2vaputaji.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2oxppuybn.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2rdbhwdry.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2focdijsp.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2aqyvrcpn.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2rqneqodh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2wtduplqc.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2uqefabrj.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vookqbub.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2trgipkpe.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gt2kqauualv.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2brjyjzkm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zshkyfpq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2gvfqjnnp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2zkhfmdpb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2nzdfkmcl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2wrmhqqdo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gt2hnxofznv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2heojxxns.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2ccbaziiy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gt2htgznjik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2mtaqkenh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2ssgmjphz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ttfsfxlg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2kjaeddeg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2xthrszcp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2augewoxo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iynvbxwv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gt2qquqbdra.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2zdduuogb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2nvpaxlix.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gt2ffpwfmfu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2tttgljiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gt2nfbkkery.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ehjukadt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2mjfbidly.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gt2mytzlwfr.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdfdnwmp.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gt2odktmzrd.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2dmgghkyl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2ednenkym.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbhamzvk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2nytobmvk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2hfdljlak.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2xnvaduxg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2ytwrfbou.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2hiarzgfy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2qfjtjabu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2ryajqevc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2zeovfycr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajwsioti.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gt2ifsylvoy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2akhgnvel.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gt2mwavqbzi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2lwqknarv.html


<!-- 参考信息 -->