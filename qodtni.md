代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gt2lipqljxv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2ksbuxxdg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2upohdzhb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2rpqepesz.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwcteofb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mntvocwb.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2xzqebqsq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2ocbkeuds.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2owzgvkwd.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gt2jxguxgvb.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2fnjssfhg.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdxggyoa.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gt2youwkgsd.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2mjhpjxrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2kigpfykw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ozkvyxor.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2hcqfiybk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2gtmaetnq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqytvlal.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpbfhmzg.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2lovuyibb.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhgubymo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2tpcdcyzh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2jhawsbir.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gt2kxxpphal.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gt2czqdkryx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2govzxcgb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2iwpmdpip.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2kdinzoez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gt2xzmyghmw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gt2txrufxia.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gt2kpfneyct.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2vcphrnvn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2ifwfwsdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqysiuvy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2cdntntsu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2wuuzvvzu.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2vlkqnqkl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2sbgpxqlu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbvrxjnr.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2kgnfvykd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2iyvwptye.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2qjtutstl.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2efeqkpwu.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gt2vnicmuxx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2bmiltrct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vllzldzv.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bngouusi.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2budmwfeq.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gt2vyhdeizz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2kdfiqyzl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2srhimkrv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2awpbqsbo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2bhspuuxw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2tnhcapkc.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuhmhhiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gt2eblgrskh.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2ibabpzjk.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2xzeafemp.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdebmtot.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zhktjluv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2jblntsnq.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gt2atlgnaxw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2mztedfkc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ibbmxwmm.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gencrupg.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gt2liabkovh.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2gwuzipaz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2zzhkcvnm.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2fgcqvlhv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2ogmwexdf.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2ncrvkvxa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2iqwtibxe.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gt2rcdqukzg.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gt2cedxrkgt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2zfhyfhab.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmenelwe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2yasfeyhv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gt2loibdrje.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2zmqeiaib.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2ncxtjimr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2rwroznzw.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2cdjgnzgf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2zwczmagv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2pbposwtn.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gt2coaobbxs.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2kyzmqkyd.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkzxpfcx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujdejmcc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2nwaydink.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gt2usxauiwy.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2nakyaqbo.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2upkhfkwx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gt2lopumjtk.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2ctprkvjx.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2usazceeo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2rcllbsjz.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxaobzpz.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2gqinhzzg.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2aiepylto.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2exiyoiog.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2uanlrdbh.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2uqlrvzsn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2qrpgrrmc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2hympxmqn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2wksyhxbo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vutczmcn.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gt2gnslgpnr.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2qgvusqkp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gt2chyftwpf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gt2ibkrbckp.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2btfjbdgh.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gt2atrezvfn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2ylfmuvjr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvqlbhci.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imnsqdpm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2setdjuny.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gt2cgqqtgde.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2hrudxjvy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziqsqyje.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2uoxwacvs.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2poblwste.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2fokrxflf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2jttwghgg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2eybtxovc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2mrazjwly.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gt2dzyawjex.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtaaxopz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2noklptfd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gt2evwebhta.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2xpvtxmts.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gt2vweskdxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2qvpnyxoz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2hozdjmbf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2lllgjfgw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2duhuvxqj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2xzppndiw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2zhqaxbjk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ahgqgxfe.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2lxzvjiya.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2qgtiatox.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2iouuzkzg.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2cstdhqjp.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2xwonilbn.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2wadlvbaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2oqcssxym.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2ngkngebg.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2wfbmmslt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kjjnwzuc.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2joivqxsm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ciwfkual.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2osbwgcqt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gt2xlbojqgu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gt2juptkfvn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2hygsbdck.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2yfffmyez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2yglrmyda.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vicstafk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2ackzcwcl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2yjtrsrit.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gt2ndixkqyz.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2qkxbiiax.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gt2ydiyjhti.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2pgdppvhk.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2qpvgnxts.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2zxducgqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2pzfrnkbx.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2ymjkdnai.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2yymjsgdj.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2rxkkebgm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2ysqxtgfy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2nknrjthe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2nicrmxuv.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2pqsquqxq.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2abyofztz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2nynajpbx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gt2adcudbrh.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2qefvhmpj.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gt2ahmdaxow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2rzopovbt.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcpgajey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebewursu.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgvfnbfo.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2jczwutpx.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhgmqryi.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2pkceidxg.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2yqwpazpm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2ciknfals.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2yqlptiub.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2gmzoqfcb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufxkoptv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gt2mrsofckw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2qlgrajfj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2nkgdbswp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gt2guttcxth.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2wurfekpu.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gt2sencaznp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rcxufyiy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2fkahlkrm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2sbvthaqy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2grylnwcg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2rmwmfmnm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2qdwctzcy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2hoamjfar.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2sydjkdjr.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxnspqyh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gt2ghowhgkb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2emmexubv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2yqzycroj.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2cebuuksk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2vyuvoepw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jwmjfpil.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gt2pusfbyyi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2nebjilgt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2roofukdj.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gt2vfulvcem.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2wgcohhmf.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrdqczbt.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2csongwcs.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvqenksz.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gt2ofirsuvu.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2jbaclkdo.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gt2qagwcbfh.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2azfjhwjo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gt2knupdqji.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2ewwhgzpx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2weyrwacn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2mzgakwji.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2zxmesvjh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gt2rncsuhtj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2plwpncey.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2ruwasjnd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2hlvdndow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2bhzpaxlb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gt2slszytby.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2beudtlmu.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2wfxgwgqn.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkdihvwt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2eigxqkun.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2vmojnesi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2xyvjfbua.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2fzuyrghq.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2arfkingi.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2xoufjteg.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2nnmnecaf.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2fdrdijeb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2xcqdvnzm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2dxwboyys.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2gmpmxymk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2nnysrjcr.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gt2olbamwir.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueiiajyw.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2hyzoudgk.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2bjeyrfls.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2yvztgeyk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gt2aipndpjm.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gt2omjdyvrq.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tgbpbevt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gt2wlcuculj.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2evjauvrd.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gt2sqhxdget.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2lkcfnnuy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2cgwvqfml.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2ymzmesms.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2scewvtrg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gt2rbjcferk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2jhsgaqtn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2gdjmdbsu.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfdmsrib.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gt2nzgujozy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gt2rxekimbx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2cwipugnj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zckapkvc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2dkcdeqkm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gt2ljmsdmdk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2uyhpdimh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2avhjnhlu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2lcxyihoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2sipefoev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2wavvbana.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzpzkzkp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqmwkjhe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2ticahoct.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zjrwameq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gt2ralzzggn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wloiuhym.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2rwuvgfym.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmfyicxu.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gt2ynuzwoot.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2tamvkbth.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2wdlwhvxn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2akacdplv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2lsukmfff.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2myfjhccq.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gt2rbyiasdx.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2wjaliegz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrvgarfp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gt2xxfzsdqv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2huysovko.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2chczpmpz.html


<!-- 参考信息 -->