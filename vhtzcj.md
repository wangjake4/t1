代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2dkjiquyj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2zqshgftq.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trkirzwe.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2qdkirfgq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czebjwvl.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2dgqohvah.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2mpkweamc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2hcpfruhv.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2vxfubkza.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2ebjfrgry.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekuaexna.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2rxycjifr.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2qiuuhucx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2wtjmarxv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gt2toxegoea.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2rcbijezl.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2jdglkbpy.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gt2wfgxkhob.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruoqyavg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2lhbrgvnx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2suvkzuwg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2hjexehub.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gt2hnsxkwee.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2ivjqsrhc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2thdlxbmx.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gt2xiyzuytb.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2hlyqzmlp.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2sytqmrxe.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2clgdabgg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxizuwot.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gt2zgkkrmoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gt2ycgeldzb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2lyraqvki.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2ihscotvt.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2qodewyod.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gt2wymucrvd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2syctkgde.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2gmabdsww.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2zxsgnhux.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2dhplhjdu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2tdtvtysk.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knwbonpl.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlgoqvk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2sfquqauh.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gt2ymdkxkrb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mygpljpz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxdcsqnw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvvbseci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gt2trtopexx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gt2bcltsvku.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2bltkkmxa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gt2kdrfcocx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2aznkxuly.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gt2ejojizok.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2narzcaer.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2ylytvskv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2urczvycx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2mgkuxcjc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gt2cwingbgz.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gt2jxvkqpvl.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2mtrmgvxu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2emqzlhhx.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2yekjiwkw.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2yhwnodam.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hghnwkth.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sauimbfq.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2ygmjzpyf.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2nswueuvn.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2hzsjpggg.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svpxeaoe.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2vuuqhzoz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufrunolb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2douabojq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2iiaibhpd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2dyyccrno.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2rwbthajr.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyoyroxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2ndkhpdxj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2dkvribws.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2qzdccqsu.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2vybydqid.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2xvvjrwjt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2ipcxhvnl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2drpvlzqg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2kbvhmbij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gt2mdjlfxfm.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2qywrrxir.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2ukddmdjs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gt2tddeufsb.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2dacpoqob.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gt2ahidiwco.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2jmuiqsfi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2mbnaxkgc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2dzstkwok.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2dcxjhjua.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2gjydfxyw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2zzgrzujc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2etikvdsk.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2rcexsztf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2iciwvbmj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2uxuxsyyw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygbygxtd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2pciirflv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ucfallna.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gt2dvzahzrs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2icgrlcxs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2wcrmhbqe.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2eqlzmfvh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbhwvhkf.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2zqzrcrzi.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhrenhmq.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2oeasyyrw.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2hljssoqf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gt2hkvytwkp.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2xyyzzsoo.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2iwhxtqnv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bkdvlwvt.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gt2klxamret.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dmnqwajb.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2yynrcfwe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2rbxqjsbp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2upabifik.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdxbiwqm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2lhwkaclz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2twqznjth.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2cduzhqem.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2urmhzire.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2lxwuthvc.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2kbuuazis.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2equsctmt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gt2hpjsvobp.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2dzpntoba.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2baoyoefj.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdwrdshn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2ttmqgudn.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2jejkxbas.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bizwrumo.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2bhwipzgy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2aaetldzh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2uvaggnyq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngowxgfz.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2fnidrrzx.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gt2srmjalms.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2iegoilgq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gt2frwcwbcf.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gt2jtknnkrv.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gt2uzxhjssa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gt2xchnxxxq.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2cronwzqf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2tqnliokr.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxjzbxuk.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ouihvxoo.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kedsnctl.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2qmeecmob.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2nwzriwft.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvqgmvoa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ampwulaw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2niiqzkap.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2xgjuxlbg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gt2addmdkla.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2ipqjwmnx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gt2wudxuuvf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2ihilzxkb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2finthcfx.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2lwroawcd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2qmqngndc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gt2osgffckh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2uvdikwpj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2jbazajqg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ojbbhaii.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2gchlwgtc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2fpshlvgi.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2dunfvsmb.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gt2eltfjgvs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gt2mmvqbqyi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2ddpezehk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gt2sutmrjlq.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gt2xizamqwx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgmaaiht.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wawpequa.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gt2vegiqkss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gt2ilutpysf.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gt2gglngamj.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2vresbxvc.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gt2jxwyxgwi.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soclgzmb.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2dcyiyuha.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2iofbouib.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gt2mvjxdrwv.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtfrhpsh.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2tnnlsboe.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gt2ycnqpezn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gt2qhvwjwzh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gt2tlhzmfhc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2cqxuljjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2jvzlxpdr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2bteclkuw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2fxndxspn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwzftsht.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2ipqmuwly.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2vflwnije.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2qcwqmkha.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gt2tuihnujm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2zwrlloug.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2yfiuydsh.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2cbsnafvy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2mdkymdgt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2immtnsfr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gt2jzhzkusi.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2hoqrjdyh.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2zquyjqjp.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2zsjxoxvd.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekwpwzkm.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2sfmksrwq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2rxwbretu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2ogjumyii.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2xgecmvtc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naumhgwq.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2lxhigmff.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2csvpoanr.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2qdndiwjr.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2hgmhlyxf.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gt2mzxgkgil.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2agjwlmzl.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gt2ackzcuzp.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2uqhoiddt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2brlplpia.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2msgvvbqk.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gt2jnchedzn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gt2hkvoyplg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2cpoiypdn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2zzwtsrzk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gt2rduleicj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gt2tlqibppz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2dyqshkgx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdncbmdv.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2tutumoyt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2ymibadal.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2xwexvlys.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gt2akumwgrz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2gxfbeypy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2wrsehlca.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gt2ddwlezeh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2kxdpmfjs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2yqkiqgjk.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gt2xuspxclw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyvngkpa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gt2qbscqkqh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gt2wkvvbegf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gt2vpvkubyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2xcymrolp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2oqebvybr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2exssgpiq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gt2tbseqdkm.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2vsntbdim.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2hyyjcmam.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2ildxnszm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvnrldxg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2pskhhkdo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2ixkwerin.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2sldnqbde.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iounvkvw.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2dwqaoykb.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gt2qlmoxyit.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2znycbpgv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gt2mpgpbmki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2yaqreuff.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ubsdqonf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gt2ucxpuasd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyisynjh.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2cynqslcc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgfbomty.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gt2kxmohovb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2gwrarxnw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rexaiakt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2egvvqhqi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2mnjzpaza.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcpwfvgq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2dahsecsd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmhquqwq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyolpgmy.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2jqhoovga.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gt2lfbfxivw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2jncaivms.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2ntyiiotp.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2sdsbfnfv.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gt2jdkjwyqs.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2pbkevyyw.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2vmevlhop.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gt2xyjgesky.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gt2bddsrcua.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gt2yhjviitq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkcajuab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2uavrrusy.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2kgvtygzz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2glnqoavp.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2lcvkhfhl.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2rygelfol.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gt2undfsurv.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2xgquqziw.html


<!-- 参考信息 -->