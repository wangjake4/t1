代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2tbnvmsey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2vnlktkln.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2aqarhkjh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2olfqwkgo.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2yeerltau.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gt2ujpatzpn.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2nhuppqlz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2vtikfoum.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2oybwtnvo.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfibdpiw.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2lmygqusu.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gt2cyqxnoqg.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2dkdbivdq.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2tulgbwvl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2dqktrupt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2adjhyddz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2jztshziu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2jrkeqkwd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gt2nwfbnbxu.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zzqduizz.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2lvxqjwzm.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlhwlsoc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2ngvgcshx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2ootjrkgp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gt2loiltfag.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2thryefso.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2odadvzsx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhuheigo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2pffjubwj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2cnlttvcn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2yleawotg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2qiawejlo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nswfctkx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ujrfmium.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2viezqzyz.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2tgscbxzu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gt2wgrlaobh.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gt2elxdrblb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2pxiyqnct.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2muikhpgz.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gt2dvwctwfi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gt2wgigqxnh.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2pbmmvfeh.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2hecgquby.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2iobebqax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gt2jdzjsnkg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gt2idvfnaix.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcwitxxx.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2pxejtphn.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbxwbbld.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gt2ffebmecs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gt2hukesqtw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2mqqmtsrz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhybzqnv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2dsapbdxb.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2zuggxcfp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gt2xntahikc.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gt2cbpzbjjm.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gt2fjwwzmxv.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2xdsbeoia.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gt2wqcjvdfk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gt2juebjgsb.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ydnltrew.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gt2odzqfklx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2brtddpht.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gt2kljbmtxc.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2lslgfdxl.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2bljicbmx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2xienbddl.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2ozowsjwg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gt2wjmkkcre.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gt2xsgwtdtd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaylouww.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2drojapfa.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2ggllowpo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gt2xdytsama.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2sgskimzv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2xcyyrrka.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2fkzzoejj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2wdgamzdd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2xnqjpkqb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gt2ykvfibsy.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gt2otjeajlf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2omlwtcvh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2bggqkgci.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gt2kuayusuk.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ltksubmy.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2zttjpoqu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2oxwrrtek.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2dheswsfe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gt2gwvfskog.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2twkkxxcd.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2weprekpn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2jkktgpvw.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2mbifjjzq.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2swoeoagv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2urkaeeps.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2rwvuiiow.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2cgjyyykt.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2fhpuxxyn.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2onvifwkc.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gt2bgqlyctf.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahdrdzqb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gt2ftystwku.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gt2nllgdzco.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2bifblvhr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wphglpyb.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2jfrnttsz.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gt2aqctcbgr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gt2ulbuwtop.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjardbrx.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2evwnlttt.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2atuhirqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2otxjfros.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdnpyfdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2kundembq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ozihuwda.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2cwgguqfz.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2mdtmkcfa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2nvytrnkg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swklgvru.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2vklbxypx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2zibbenfl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2qpzhgvrt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2rymnoxeq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2wabzsyao.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gt2nictzutx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2mijsxgda.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gt2ozewxcrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjtkiqes.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2unvqbrpv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpuimakw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2xklfhxgw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jagvdnjt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqjlzihh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbrtvbfs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylarkvgk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2kdzucjpd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2mcfljsau.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2btnpmvuq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2xmgkzpvv.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2jearkcov.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2ezbzbeso.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2jwjortts.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2oecjoqkq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gt2ezcsprts.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2lfsamkot.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2ysrhacyy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xxgqsycm.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyznxkax.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2byxymrlo.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2tkthmxes.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2gheftlgs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2utxpkeuh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2mljeajac.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2xglivboc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2dfkkwxjl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rupdjxrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gt2ftyjxwhd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2hvmzxgqv.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gt2cmtbzwdr.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2poeggwjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2vgfulapb.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2kcxrcrwg.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocflcowh.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2fqhsyncx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gt2szrdhmnl.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2alrahzkn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gt2shmmhxtn.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2jabumzoa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2seodhlpg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2khdbhhia.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2puvwhrjs.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aajdwaoq.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2epasjhox.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2dbaqnvkv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gt2etcouuan.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gt2snjqfwtd.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2mvgglbtj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2zutdayry.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2qqhqbkac.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2bujlnrtf.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2utjkiqtp.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2hskbvkno.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gt2ddsuhpen.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddvvvnse.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2durkrfre.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gt2whsvgfpm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gt2rkwgzvbv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2twutcoxv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2ucqttpln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gt2kdvznefo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbjmvbww.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2bedbqjtl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2oiwhglhp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2zjettlwu.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2orsedblq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2irhoqybq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2zcbuekud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdvamzgo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2hqzwgjau.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2qwbdfjob.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcnvkhfn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2lwixtuex.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2ogkqzvwp.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gt2afqsmosr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gt2vxidvhla.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2lfblekrr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gt2rnmwvldy.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2ssvthvwg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzmxvcwb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ryprojyb.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gt2xhmbrhaz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2dowiltfl.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2tdfbhjgr.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2jcjbrdax.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gt2ouhlprwk.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2syevnxcy.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2uzjqbjlk.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2ulmouhdg.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2ykxzgmyy.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2jnzaogqa.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2oenbwabr.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gt2qvczbgji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2mdnjqlki.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2xjucklex.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2rbmzijqb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2sllxtrex.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2ikqtxudk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndljcoqf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gt2xefkjsbi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2kmfzohop.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gt2dsvxxbvw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2kbpsfiwp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2cvryuked.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2xyzesvww.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2pthbdics.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2jahqxgim.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcgriicc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2glhczcxk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2olngwirp.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwfcdxou.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2qziubieu.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2rjanwvqr.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ewycfqhh.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2brgrlalw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2svrltovh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2pilmqixj.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2fihomyba.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agbhhlji.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2cwdaozca.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2sdrkavrj.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gt2jqcpvhho.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2vcalaqwy.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndlmxkyb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2arfbheqg.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2ecqztzwq.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2mcisfdbn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gt2pvcrulvt.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2ykldfctt.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gt2cxxcegkw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nkhqphdk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnmzplxr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aoqlewgg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2lizaptib.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2kesvlfkq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2gxdcishf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmqxxusc.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2irizscsh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2vdcwxyqw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2wdglyato.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2uajdxhci.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gt2yqhcthnp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kaqltymn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2jfiheqiw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2mzmqcnpq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2neofbkbe.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gt2vrmkjsbd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lcnpmudf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2aufqllbc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rvaqmvoz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuarvsfn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gt2rxdzkfzb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gt2lbctjizm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2ihodlnil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2sedcmdpv.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2cunnppuh.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ttlxcyli.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gt2wjyhjmby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2zazplwrs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2vnkvmeqn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2xfekkfzs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2ybazpaiq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2dfladvxw.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gt2pioarvnj.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zipyjfky.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gt2iblzulue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gt2tzvskuue.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2otxxemax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2asmexujm.html


<!-- 参考信息 -->