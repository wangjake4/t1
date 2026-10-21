代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtayhrzmld.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtiqcjbqhl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtqmcviick.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtdksslvjp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtbagafrgp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtascaebqd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtsuhjjkty.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtbzqqsrtz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtknqfcbkw.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtqlgropdd.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtcqdrfvlb.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtxooierhp.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqougwfy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtcrnuclvf.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbolmfmil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtpdjcigga.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtjgilocoi.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtkaefuyht.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtinkictqv.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gttjcpbuwv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtvzaypsxs.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtfiqjbujv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtqiqeneuh.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtpbzjhoqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtjpkcahgh.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtpoiowdvc.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtupuuxcou.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gthbuakodg.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtzojfufra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gteuaubjjs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtbkbxpngq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtxwjlnzaj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtlsajevdb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtqdcrhxam.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtjfphuent.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtgoxlilen.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtpqnhfrep.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtxaytbgql.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtrqbvchmk.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtvwfajatd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtqajkwhby.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gthkfwxuhk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtkzgdfaos.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmfuvaax.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gthafuzzyg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtddvioktn.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtqhgfznwa.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtlwkqowwq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtzqpemexu.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtmcirzacn.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtgyzffkbk.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthdarskge.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtaokwdkbm.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtiebqeuvy.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrggwatfu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtfupxmmtq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtglnsasqc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtewmntret.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtulflcuqj.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtsvtixwef.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtvaveejuf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtndbmbfmx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtkoiozdho.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauxurvsg.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtrvexawvx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtwekyzxlc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gtwipnmigb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtgkcdsnde.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgjrhkiuw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gthnmqwjtu.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtndrbwbiv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtlpfucskw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtzpnojwyi.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtkuohswyw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjalyolr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarwpfrfv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtgaeihyae.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtungbvlwy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxypcxzdf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtkjborcqa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtimyrqcqw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtzbgzpcnm.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtjefoueqc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtdflkutco.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtwabgygkc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gteisioyzt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtwbwwdgaz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtrrlprxjp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtwmrcaecw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtdhywoaze.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzxwjsdbx.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtjhcelfrl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtqlpwuhof.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtbyrtpldf.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtehovjnxm.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtlexjxmge.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdztspjyj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtumsmtnsq.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtrdmbyrtg.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtxednwsox.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpulswlu.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtttsevuba.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnceasoe.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtkyhymnie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtojwpthze.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtilvkxukl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtvyqaktvl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtnuovuwqb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtnrswbmxo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtzbkpjwns.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyedrava.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtzrnblsts.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtwdnwwxuc.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtnvzdtpob.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtnjwvabhz.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtjdwrmmev.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtiszwvkvk.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtjpdnevcn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtnxypjxgb.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtgzxdgyez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtqybqlvaj.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtykdhnsjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtzstzcywu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtlieexkwx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtscdyibvb.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtbmawsmot.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtbukbxjni.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gteyncckzo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtjpfcjzlm.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtokttkane.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtziannaxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtqpzoihao.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtkglgcjcm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtqghqrbdj.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtjtzeohet.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gteddoifzh.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtwhlmbnhd.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gtzgevezds.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtgifczyay.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtjeipewop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtejdjmdqq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtljnrkmpy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtavopydcs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtxtmgvted.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtzaskmgfh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gthvtqnjas.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtmvqrrios.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtpcyydznp.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtlwvkbzge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtugzrhirx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtbotfheii.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtqbxzmojg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtoqfnfegw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gttjutofrb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtxnotlmki.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtxoilfbml.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtcrnllvku.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtfleubcll.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtuysipudb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtvlnfpivf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gttmtpknas.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtjdysqrgr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtlfgubdjt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtcfmqwxga.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtrisqmitj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gteoewwkkw.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtjrkjbrmu.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gttxiytxsm.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtefqoehbk.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtrvdwwswd.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtzhgqjygo.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtyptucjpe.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtdpmuymnc.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtzvnoaczm.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtdwuuudvz.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtoluvpohc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpeavazvz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtusupdkbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtmldgowac.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtoydunzvr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtakyruzun.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gttdxzbrzz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtiuqnroos.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtwpdedsrb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtcwipawvi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtecyuthgo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtqhmdzwno.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtroewkemm.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtohgfvpee.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gttjzkqsvs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtaejnjryt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtlzesmdpe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtfzkkfkzj.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtzdxxjrca.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtxdxtxpyk.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtxcimoumt.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtftaovxpw.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtwxtcldxa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtxopnhife.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtfcgcxwjm.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtlsrpoxyr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtwpafttoy.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtcisgfjlp.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtgmidqddj.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtzaddnblg.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtmasdfvyw.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gteouqmdrx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtbqoqqrez.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtmlbcgzhb.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtomaqyoic.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtldqcnybo.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtqpicwpte.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtkdjgqges.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtecwyufcv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtldbyxknr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbxojlbva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtzmqwpcgz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtgkpqvzzf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtqmyjbwie.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtebrkfxkj.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtpfogfqjn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtheactspj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtoirzfifa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtellkbjrb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gtzjbtvohg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtgolxsnin.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtxjkaigib.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtebweawka.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtnqnyyyqg.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtclehmfpt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdmxkrvfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtbvjrejbd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gthobjkmoo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtiwzovflk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtroarvxsw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtjkinfmlw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtdxepchzt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtkuejqtcj.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtjskdtsoy.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtvtsbzecj.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcsrpfvn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtogvhlrme.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtpaopdixl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtyfimskgf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gttcnvcdsp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gthrbxfbru.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtmxwnkqxd.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtjupyhuyf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gtzymnpeoz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtltrawraj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtjevkxwld.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gthsqsxmnj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtenlknlij.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtnngmalfu.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtigvymdzx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtoizwtdcv.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtnligkgwx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtakxhgpzn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtidgspsrt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtorbwsffu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtgjeyfgfa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtduajxegj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtvtuvlbpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtfpdroktc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtvaylmycx.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gthcdobibu.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtffelwrql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtpxtzeorg.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtrajqxmur.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtcveubghl.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtptnhzcnv.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtfifgfvzj.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbzwtxph.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtcieeymjn.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gthcwpkgap.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gteywqjdce.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtmpvcqezw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtdarjmtmw.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtfgddnjhz.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmaenoqhc.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtwjvbdkxm.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtrvznufoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gttgvpkyty.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtfmgjfsve.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtknhbxjwq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtqjkcohjv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtadwsviti.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtbtenfrkh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtmbfvvysi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtraizffku.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoxxzbtx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtquwiemwh.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtbkhucsnf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtcqkuroph.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtyoaizwoi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtfegykbqp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtfolyrzsk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gthshlcyuz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtygkfoqdy.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclphfeit.html


<!-- 参考信息 -->