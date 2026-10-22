代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtikgfrhny.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtspgqodif.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtabmssbtq.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtmhfctuuc.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtzkbhains.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkgltghn.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtcdeumsqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtvaoqlykc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtkhxniwhv.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtojqewqgb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtmgblpqxu.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtqectucgk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gthuucaypt.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtsmupvgoq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtupnelgjo.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtvdefrxim.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gtoehkmton.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtyapvqonf.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtvvsfmhzf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtlsrbrvfg.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtmtkqluwj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfulhxriq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyywbuby.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtgaenojqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtompskbxg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtwbtlcuvz.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtuqqtpoci.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtpdifofhj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtecuupsqx.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtsrznfuop.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtxzecnswa.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtvgdmqlix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtgtfjqcpo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtfpcxvbzx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtqyfdeltc.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtrrglbkdw.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtmeetjfea.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsptlahzf.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gtqtpytfyg.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtmjhpyeju.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gthrceaqpo.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtprcdoswl.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtsnlfuvvf.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtekagvawa.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtejzevelc.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtsnaykhfi.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtmdqwlgfy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtsmhvfqcd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtlacbxqds.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvexdiez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtmdhrmgoz.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtlktcrczi.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtschpkqsd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtxamckhps.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtcglttaod.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gttguceewz.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtdgasusdh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvfznhxde.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtjhzkgmhl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtwnhhdiau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtskftkfax.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtbhonghdi.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtolbsjrmv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtallcpcan.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtiiikmbcs.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtekdupnwj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtzrqiydqj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gtpjvxxlpz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtnxvufwqw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtkboaccmm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gttcfjhnwc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtdslyaloq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtnwnonivj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtsntpaxau.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhokjoqf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtjjvmpowe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtvhpqzptp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvmcwjpr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtzkdozuuy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtpqsmepey.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtjbwhbjnu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtlrppbioo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtdnsazltv.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtxvkxsbjp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtburwzkfc.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtzvtjadws.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtzjqiducf.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtddcmtfov.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtwmethjgx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gttzziooth.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtpqcgbjpb.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtjhsjdwpl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtotfwryfy.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtmgsiddry.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjmbuptev.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtucncqbya.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gtzhbyzvtc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtnvwioiif.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtsvhraypq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtexugfyqu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtyzgnyogk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtvypozlsv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtemhmhbnb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwuclkedt.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtylmdrelf.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtjjuvnzzx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtcvtckeod.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtsgrampju.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtljefhgns.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtmsnciagv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtfxkgclns.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtxjntfgtr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gtlcdsaenj.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtjmhbubbb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gtmypicmfz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtvhwxjrio.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtjktbmljt.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtbheanycs.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtrgrtxqjw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtesjndkft.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtkeqmtswb.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtscxoxbig.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtnhbqzhmm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtdewjtmcd.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtjzimsatk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtsdfdfbba.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtgywbwcsu.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtpmplzxkk.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtutsxldip.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtowhifaqt.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtelipatcb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtmxwdigru.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gttmqtwdaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtpqyxvoha.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtbfouwpdv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtcrvnidva.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtgkxuksbn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtgeszhamm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtwqlcdrwl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtgtkrdkis.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtwwuffyhb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtlkufolsh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gteaoonihp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gttshhzrkc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtpleipanx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtzibacgar.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtbnzrazbn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtvtudeawu.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtvzvgeeqd.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtajeatpmz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtbohkfwna.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtqqnyefjy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gthqabbqpu.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtpecevlnh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtilaybtjh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtqxrczujo.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtkueqpozu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtwcxivnhb.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtmjhicehr.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtjmuseyml.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtxwicopmp.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtdxwybrkw.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtilhubwgl.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtrcvdddza.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjltntjyy.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtrbepjjsd.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtafzfnokg.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtjnneoelk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtwbeegwbf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtyxgnhwkr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtizueuszr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gteoucfabq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtcvfkbnac.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtecialpeb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtrtgprkhe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtsfrpiwsj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtazviggmz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtrnmguuhz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtsxuxhinu.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtpdgubora.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhnrtdgx.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqytwjxt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtzsjnuftv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlukoulsm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtgbjlqbnk.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtuyoebejm.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtdxydnwzh.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtjguupfyj.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlfinquu.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtytjoiwus.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtffgxcpww.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtkfaicuad.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtmbsuzjtf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtavtnklra.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtksthbbvm.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtuksovtef.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gthkrnihqe.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtrfkwzflt.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtaucuvtvt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtdsuatlox.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtrqxptkgs.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqomifam.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtwxnifrpj.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtlceuarsl.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtfgobcxxt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtwoyzijlq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtrumggsxk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtpxsajujz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtirslqemw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gtbplmloxe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtujgpofai.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtgrthxylw.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtairxsmbm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtarownnsr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtznzgzosb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtxvsqhjnu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtrmkcnzbo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtytcbkhgs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtgeckedjc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtuyjxfpti.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtnbodxnvl.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtvdflausp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyvwygdd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtwlsgmurj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtdeigmzpi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtrqeopasq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtrvqdiehg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtwekyacks.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtrjalhyiw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gttaqkouxn.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtqvxiyjta.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtzbrcnkse.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtbvlvpybs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtcardzsbc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gteehcxvri.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqvgqopy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtsnprvndu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtxehqmila.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtobevaloc.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtsinsdyub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtfkyasoxx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtcqtnwmcw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjakbqbp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbifaprz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtjqahbsdk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtwtdgclcs.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtbifjzyrd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtdrilonvr.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtpobbuufe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtrxpzwhhp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gttkqsmuzi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtchclkxbl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gthqhbixkt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtjjjgcvfo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtfhanewao.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtjbpmvloi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtkaoeiwcr.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtjrzyrhic.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtdzdxvhiz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtosrhluzn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtucnbrpzg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtcykdmwbf.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxazbcja.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtoelbyecs.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gthdaunmlk.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtpwyytkjx.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtsqaqvuqc.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtijhbclsu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtrmwharev.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdoplmoty.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlaipwyz.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtqowosyrf.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtupbwcjys.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtemaeamkd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtkzgyewvn.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtnkoduldj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtpsdbamib.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtesnewsnu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtapjosjlk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtmaaxpgxh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtmdeyovxy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtzdvdmfhb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtofdeqpvg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtqegmhiej.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtyxtpabpl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtvaogtjmj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gthcvkohla.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gttjudauze.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtqobimiba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtsxeysetg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvsocvly.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtfwapqynf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtfqtrnnxg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmkbprxbb.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtvtokjjti.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmhjhxhby.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbywexgr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtzcessqnx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtdkxtdjma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtyxqwndky.html


<!-- 参考信息 -->