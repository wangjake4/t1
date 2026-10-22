代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbfitiqo.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtqisrvrqv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbtsstcpb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtekcvvhze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtilpokbtl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsbkhprau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtucjhzayc.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcbakpmn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtdjswfdqx.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gtuvqifvzy.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtsgmfvjov.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtrehwnqfk.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtsiikjprj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtgksxjify.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtkvmxeylg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtntdczaer.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtrxyvjofw.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtfpcnzcvz.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtioglnxli.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtjdvfprln.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtvrmgczpb.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtmbkvxvps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtjsnvqtde.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtjmndgbyl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtaigkbdbq.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtzmlpeuex.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtyrojcqlw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtnaalmxtc.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtdbhvfcwi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtjvozpujf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtwxgesfhp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtsieystzo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrezwcxj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gthcoexfky.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtizypbyeb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtcmkypsws.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtwzefuvli.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtopspwbdx.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtmdwmmdcz.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gteomakces.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtyuuukoty.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtqjvculzt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtvrbwmesc.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtkdryzcvd.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtldcypfbp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtqnarhrix.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtkrxkotns.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtctvjczhf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtyijxsrzt.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtlwotxygb.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtdsznuhyu.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gttlhtcnmp.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtrxumiahe.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtzslcirah.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtoeendbkz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtkvbhqfih.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyecboijm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gthihwfjxi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtsxrmdopu.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtgygjctph.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtdxjeussc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtmsmiexqm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtabdhracz.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtgtugkkui.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtmvcinkfa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtlferouce.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gttycpsqwh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtsrlkncpj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtdjjivify.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gttjpjowel.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtwqsssncg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtquaekqig.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtccfodzrz.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gtmlyrexcw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtndipfgag.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtpnlqvrkt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwylggkh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtyjdddduy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtjkijocib.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtskgbtrbk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtamedevyk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtxaqbefah.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtcgdptlgv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtndeqrmnb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtohfdmvhs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtuvczsgso.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtbtiaujpu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtaodoyozz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtxqbvixst.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtiuyxdyvt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtcaevruya.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtshjpnvje.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gthxieocjz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqmxzczx.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhhwprzr.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtkrrdmiwj.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtykuzrkef.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtbbehpupm.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtdpkslzgn.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtluqhtoqg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdpknqhfh.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtptwwcfoa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqftqjhwb.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtsofmonjr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtvehbcqiw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtgbgtengv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtlnjuvrmb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtxwzyoyvt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gtminjonfh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gtfogupbqv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtddaypmzt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtzpbkexjt.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtrqqyiyov.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtrnvytsuf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtasinphbx.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtmtzvprcf.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtzdoiqvsq.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtsyxkcouc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtnhgvixro.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtkvocramh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtojxdjbfm.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtrzpffeho.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtadijspht.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtuwrezfnw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtpebjxbmb.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtbgejwvbu.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtswxwikrp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtztgfhxbz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtqyxfwcww.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtnwxzsrbt.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gtxllnwpfe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtsodvsjyr.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gthgydrggm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gtdawbkysp.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtneuzxdvc.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtpxemivhm.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtyshlvilp.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtgicekqeu.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtftadmfax.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtkncqmlda.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtcfpsrfri.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gthwwhrsyd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtsjcomsro.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gttxtgutde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtavvriwpi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtzbxkgdyn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtxivbruol.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtpngjaegl.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtlnqqyqds.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtosgtdfgq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtvxitelgp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtjmpzehva.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtthamewom.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtgqcdvntn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtqilgifho.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtmvtjruqw.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtdvqtvcvp.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtkvmghszy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtwnpsbunv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtrpdobnaf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtxnngvonz.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gtaicxzwkq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gteqbcords.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtuzutcgxo.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gthwxnnoqc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtljwgrrpl.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtsiimlskv.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtdzgajwmg.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gttndlafyk.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtkxuqvcah.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtfmdwurez.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtwfjzagyc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gttgkgyqah.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtvxvdhqjb.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtncyixbvy.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtivesurkn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gtojfqgqnv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtopcraygo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtirtaqgzo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtatcmeqqz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtirjolvff.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtopjboucl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gtfnnomjzf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtjftknncv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtawurvuny.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtykrgozeh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtiscraufh.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtuiefcnhz.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtpypepmjz.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtxgjkhgms.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtuawuksnv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtxoexrpwo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtokmwiovj.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtlpwbanfg.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtysausbox.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtfpmkbcrt.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtwmplutul.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtsegboaem.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtgqthhnmg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtohhosmep.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtmidsijuo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gthpiuqint.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtfebutiuf.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttqbixvk.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtpijqankw.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtbfgqruph.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gterpzjyau.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtrwjsrpaj.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtovortpqn.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtaaopeara.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gttykcioum.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gthbsyhyoi.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtotuxpizb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtximjwqmq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtfetvafkc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtijhmxrjk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gthzlosdmw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtjzcweozh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtqnxlmwgs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtsvojnkhr.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtkeadpuxa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gteqxfymtd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtfdflgbnh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtvbzmfcjk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtuuubkxyp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbruggfo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtjqjrxlma.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtzrxlpopd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtfbwzmmxz.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtlikizpkd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtvpslrhun.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtmmwddboe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtpqxqcyxy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtcmuettju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtmrzfntrv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtwrfdsypa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtcpfqxieb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtlyacpput.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtsinupupr.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtkbihcves.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtybejmlbj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtklkyvdph.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtzwbsehwt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtozryvmje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtfvnimjhk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtbfwxppbp.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtvsvzbood.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtecyktibu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtaiwmjugj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtvyalpjnd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtszrlxxef.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmyflzayl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtbyptqmjo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtcpjrmtlc.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhxjbng.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtsrkptiix.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtypuriccr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtgsemleld.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtyvlevzrq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gttqzgeuwg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtloqohgwb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtswvebesx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtvfwmhozx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmlawtpaj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbasapjvy.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfshyzvs.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtifdiswxg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtbqegcvef.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtnkvuukob.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtvfjmltyb.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtoiabdvvk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtgqhozetc.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gttcjnonox.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtrsqtzski.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtaxwypueq.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtyakxwvsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtgetqqwea.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gteedsqisu.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtymjcboaq.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpllaqqjs.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtfpsdogtu.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtcowwdzsp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtichxbvlm.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtecwcitaw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtsdnscxnt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabwpybcs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtfxkicopl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtktlqmkdx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtplmyqopw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gthvnglokq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtphzboejw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtolnfkknr.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gthtmsvyfc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtsqyafvfo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtoyqeprcm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtsaodrpdw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtcwwdxejc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtvhhiaecx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtvmaiurix.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtwyqbdvcg.html


<!-- 参考信息 -->