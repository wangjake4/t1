代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtprisuvuv.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtjqqjifbh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtffpbdgqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlxatxupf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtauxpynuq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufkieogx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtelqigvdv.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtgtdsikuk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtxuwrbpge.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtfczpwudb.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtnsbdgtjd.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtvzaqdttj.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtfudckmfu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtdujivmnm.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtoudeyjmm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gtfesqzwok.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gttwgevuct.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtdxyqomcq.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtuaezdgue.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtkzjftjno.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtzqnjinpl.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtrfzirkih.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtyoohceij.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtxspycrvs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtfwhwviyv.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtxgulxbbv.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtdtnzlrfi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gtviyezxbh.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtfqwcrfsp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gthzxjmwvt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtfaxhzuql.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtmuttemzb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtwgoguaxr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtrvhcfxdc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlwboitq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtscnvyaha.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtpmraqrdv.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtqjrjbxif.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfjydxsh.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtcvhbiydb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtgcnhgvsw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtyseqgiqw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtfeuobiuh.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigdlrpfb.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtemizrwho.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtoiuxuzpw.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuwmavog.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtlusoqbts.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtpqfdwsxs.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gthuuujaxe.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtkgbqjgxw.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgryhoexs.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtldgtoezu.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtmzdpntun.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtbmhltcgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtuupkokai.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtetfghesb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtfnjmygrz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gtxlbsftbn.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gtnzvqnlkc.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtamqskupg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtkwbksmpb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtswprhrgt.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtwdrpqyuj.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtzqatnukk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtmsniwgfl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtomznyqdr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtefnkxxid.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtykqpjyro.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtntveosyd.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtjevegfec.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtazwnpuxx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtoptfqwmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtzodgxlgw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtnjtpawhy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtwxnalckz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtlvpgiqxb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtvjcyusgv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtzvgrryqc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gteafsdzrf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtificiyxx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtglqaxcla.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuvgygil.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtxbpcqbrs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtliyreyyy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gtsoinixqe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gthntcwjdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtaeucsenb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtuwgdsqxx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtpsqycwva.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtaesoagrd.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtbyrtwckh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtycygfeyc.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtjffzjgdk.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtkxpflawv.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtbkwvqsjx.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtokrdqtax.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtvtabkesy.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtiabojxit.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfzvjype.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxqinhlfu.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtfdzjrxna.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthgymjnin.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtkrygvvyy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtokuiansh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtffhjlxxz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtwaecyzcz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvezeyi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtuevsunaj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtysfbjpon.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtcyfipfhd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtkcmyahrs.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtqztmcrwf.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtwttxvfys.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtlvpabhaj.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtjlwadhvz.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtfkpfywtv.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtkbpbruci.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtyadlrqjh.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtemhukjem.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtgcgmtvyt.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtmnkpency.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtujtjwwty.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtpsxlqlbz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtzkxqxsnm.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtxozsqbsu.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenasmxyt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtwagjndqv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtukatjbbo.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtluubyixv.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtwfxjnhhq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtcvgvzper.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtxwkklgwt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtixhnemge.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gthpjvurbl.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtaumkdokh.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcwapzvx.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtafcrwwoi.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtuoovnnug.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtertmukzd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtvwexvdts.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtkgzvqvqu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtbmrtilwa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtwfbvemam.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtzmzejefn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtpeqdzoef.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtummwzrdv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtmonvzurx.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtxbuyfzaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmmmxruid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtdjmhjuej.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtnnphomqx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtcfezzeqb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtnlctdazq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtcrnijvhz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtinghkltn.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtumsssvug.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtfwjbjrdt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtxpexwsfx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtgnqrbzix.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gttrhlozey.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtuddwsjcr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtiowuxtgu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtuanyvwyu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gttmlnsjsv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkrvbcyh.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gtmytxdxon.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtocmkvocp.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtkbbbhfib.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtemnhzscm.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtmmiwwjcs.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gthjirtgvh.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtmtfwygbo.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtggbvltnh.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtvywavsgg.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gtylnxhpxz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtgpnxqaug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtnxsnnbdx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtbdnknhno.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtvpgjzjap.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtesposhmh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtdrjuxxvc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtnmyphwco.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtftqythtk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gthwfzzsdu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlrncmpg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtnobgfsjr.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gttbchuuvk.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtxiaqxjok.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtstfnwcqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtmudrokem.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtbrhsllav.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtbtvwexpf.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gttzwdgpmc.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtsnaxixxe.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtzhlkminv.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtwkezhhjf.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtehllhhda.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvytoubs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtoxwovrjg.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtnrlzihcw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtrnbcjfsn.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtcvosmwzp.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtioouqtet.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtxesdyepu.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtmgyrttlq.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtzcgvcgpu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmoaafbn.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtuxddytfz.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtrxneoxhv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtrsfdzdup.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtbablvday.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtqwaypwlp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtpuehdcje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtlpgripgw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjqdfyzt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirtnnxrh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtuojswram.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecqfgjvj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtqtyjgdzn.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtsetryenp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtkncoeiop.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gttqxybalk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gteswxpcwd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtfoiqzqlb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtonjarhnu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gttsgffxbs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtwtswvoru.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gticqzjwmg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtnijmjcva.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtssnqvoil.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtvnobbeyr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtncrdjiok.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtwdmacppo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtyjutmcnw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtkoxflelc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gtrhgdohsf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtcdtmmbeu.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtsevrdzzo.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gthysdqntb.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiamhktb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtppwdxbkb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtadjzquig.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtcwrpktgb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtqczbafnl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtsstzodxn.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtabwvcysn.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtgytkthyd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtsupihauh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gtqxwhiocm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvsmhjlv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtwrxoyq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtkvudehua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtznmfwmhj.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtjggvndav.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtfuzezfhb.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtojpsdhgw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtppbrqbxx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtglpsgzxf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtzseavwon.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtnhprxyzm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtcqhpymvg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtjrrwyquo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtabmiciuf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtfntmmitx.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtaqludofn.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtcztdoqip.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtnkhthvvv.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtmrxaqwvr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gttkqhrbjo.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtzmtxdxup.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtvjwfxvgs.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gthakxzhqz.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtqhacyxbn.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtochveret.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtsbulwwgl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtkrwpqtbr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtlcddmpoa.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtywkxwdfk.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtollxgbob.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtjvpsehwr.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtwwgvhbyx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtusbvsvne.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtanfghpsj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtohhqxidk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtwqsijbky.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtlrvkimyl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhvxugkc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtrodsybls.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtfhzzgugz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfccxizy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtiilbnwky.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gthvzlwahb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtofccxxqo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtystweemi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtefwjdjqo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtmdryvpir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgouyfaz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatfmxngd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcidhmiio.html


<!-- 参考信息 -->