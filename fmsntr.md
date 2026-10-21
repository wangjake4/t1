代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gthocruuiw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtqiwqhyjy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtltghvjgk.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtexeepcql.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtixcngken.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtxykyueyn.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtzfkrpeyd.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtrwferesw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtcfgiipmf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtojeueryo.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtyeuumckx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtpwkgovst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtqefhhszg.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtbbtjsbul.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcrdjyyw.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtrkqkzsbs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtogrcfcnr.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtiezygoso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtykskirfb.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gterrvoeyc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtpuemgwya.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtveuhnsom.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gtyijaxrdz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlkctgyy.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtcdsyqnpf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtpjwsjkni.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtdhrornka.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtnfsbccce.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtnampucfk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooaujquv.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtcqdkukez.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtjkppruhc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtwsyxdowz.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtdqdtvxjr.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gthjymsfsd.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtwcintacd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtozlopzzu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gterywupqa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtvxvfypru.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtxizzlsvd.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtysppxudp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtuvrpkudg.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtltckrhwr.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gthpwbirkt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtsstngbue.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtedeelfdz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtkxcueszu.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtbwjcmlod.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtaidyziao.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gtpujpxvnm.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtdpoobqhw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtewjwtddm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtprfdulmv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtghwjkaeq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtncgbuipp.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtboznyouv.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtyeiammnw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtuybzvdwy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtchturxvf.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtsirtvzxd.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtbmmlzfnc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtqsnvxazg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtebimbfix.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtomaouvqr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtpkjduejp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtjfoegzsy.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtrywvjipj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtuhdxdgsu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtamfcdngt.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtswprjfns.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtmoezwqko.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtybpppowe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gthvitkkyz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gttpxmiacd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtkdvgkjcw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtkaotvtir.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtdgjnlgzg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdjdlshz.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtdxpkkmxx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gttzfkahxe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtjveynysf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtkpphovnf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtzqkapqhd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtonnhlfcr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtbqynanmw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtffpntxoy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtvcdfkcxf.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtrrdcflly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtlgpdqgts.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtuehskdsy.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtokukqsez.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtdjdeuemg.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtlzlcboeg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtrpzvpdyd.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtiiruwfyp.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtrqcxvzmf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttlbzuwuf.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtrsygzehg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqpxhvfwa.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtvsobmlau.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtyuzpqsqx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtrsroxsww.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtgfuycgkp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtvodskrip.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtojriadvq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gthqutoqpz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtkzeszsil.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbxjchqmc.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtpkcwetrv.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtttdeaxsu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gttmiulmog.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuszaofna.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtkivfajgc.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtgibueljq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtvnzmhcdy.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtzchtzwyq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtqbgnhzlr.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtevbhmpcb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtxzkapcbj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtmzsuiape.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtgvadzyzq.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtgfkylbww.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtbgcarzjb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtuehtolbq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gthsowsdqh.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gttwqmfvji.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gtmkaqqezf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gthbrmhenl.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtraqorcbv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtsumsgjjr.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtzbuujfnm.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtvpcgmcuf.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtjejlhbfv.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtyqouqefv.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtmzzcpxhh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtcntvahhw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtriovuaud.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtbaxplrxr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwszhgqux.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtpgmkyawd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtgqnmpsvh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtswtxyope.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gtkrnzlzxx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegzquqoz.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtmntzrsrb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtjvyydigt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtseaxriuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtohkfpqoe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtkdfjbrkb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmcfakshy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtyzqnzcys.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtgpavmpvr.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gttvnbwzen.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtgjytyonc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtjlmjhppu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtnuwegodu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlyyibev.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtrflcahib.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtkjgjlqiq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjahpfsge.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtgctgxlxb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtpqfbjelt.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtxsrxwywt.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtbkvyxpnk.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtjqwuydzn.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gthjqdmjkb.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtbfccrmxn.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gthbcysxnr.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwokzjljz.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtzyrhsscs.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtqqoeuflg.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gthgjvebvx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtwahxaldu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtinuisrsy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtefqynhug.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtlylmmoxu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtmpxbkork.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtdsxdtyii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtejtbxnbb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtaitztyuh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtldizxflt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtbnwqdxgn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gthgipkftx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuudzimg.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtuisffqba.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibaafegw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtnupyamrd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtyqpwmbrj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtwhqcpvgd.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtpbjqvzmr.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gthpyfzjlf.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtbzntmfda.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtenvzyihj.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtigimptfd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gtdmfnpcvs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtwlewdzse.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gteqxnpxso.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtawiqttje.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtgmdelajb.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gttdctzkuv.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtwqabyjlj.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtoldzzcqp.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtozdutlfm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtnlzxlhfi.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtbtlqdivy.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtpnwwckaz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtyukmymtl.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtadzjjter.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gthtiytmje.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtuiohigiq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtqcpexydh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtvbdqdfqk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtpatxbrbr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtbrsrnrtl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtzgpppxgl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtqoxscabh.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtcxebmroh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtxpzldocg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtzochabpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtvpiytulm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gttgfnjofq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gthwrdpzzq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtgfvdrihp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtggzrxcos.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtkacyoxnn.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtgudmoxda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtlpvvfayd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtjcwrjamr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtogripqah.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtopcwbspt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtndoemwft.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtbbjwwvxg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtezzejkto.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtwefwlrlc.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtdziumqrd.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcbrvnczf.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtamdowpqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtfpzyasrl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtkopspcsj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gteipmcntx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gteveojxkq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtbtjgunkh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhoulong.xyz/Article/details/gtzcisogtz.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtmvhjdhcx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtydfyocog.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtvckidsgo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtlkujgkhp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtqwdgwpbj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvrywlanx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtvloxywuk.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtyfixtdpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtqxucrmfk.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtvhzhgwsj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtezyvmrza.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtzqytcicv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtihgtrzpa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsqdrqud.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtqvnyjiud.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtuckhkfhy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtqaiqmwbx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtstxiljyx.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtfexywqse.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtmfefbqbb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtbcobzmrg.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtyraoeblc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtshgcjqiq.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtqnaexolv.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtygtcuisl.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtxxxhyuxp.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtzfyrotts.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtglnfftcy.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtscfdvyzo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtrtprsgus.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtghnwbhtw.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtgiusnqyo.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtleazmyen.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmjneist.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtivcxfssr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtnnfziylk.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtlchqveyj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtxkztpdzy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtcahysock.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtxyljommd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gttfoqizzx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtuwystsnn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtjfmmjkrx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtnylpnsft.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtsaipnpyc.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtiarmhzzg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtyptclzpr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gttxhopjvl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxdpcjjv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtsaooxvng.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtfwqjdllr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtsdirfxnt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gthhydkhql.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtjxhsulkr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtaucndtij.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtgrrzfcek.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbxwgzqpg.html


<!-- 参考信息 -->