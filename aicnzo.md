代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gttzgvuide.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtlriungkx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtrdsucevk.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtdjaussda.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtsuwsjufv.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtnbqexqil.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtnritaeks.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaszalxgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtufbxlgyk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtyhvnzqtr.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtzmfcqgod.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtzhvdupnl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gttsowjbwf.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtvqwlykwy.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtgwwruxsn.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtuanspsxn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtddtnufwi.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtdovobzdz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtsghnmqpx.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gttgcbnxua.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvugwrhin.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtxzdajvmm.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtmarzcmxl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtnyqowtje.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtqvbayiqc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkziivbd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtkwxxpbth.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtsybzgmmj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtlobktfzd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtxyptczyt.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtnsnereex.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtkftqezvj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtmfwayhdo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtvanjdnwp.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdrskjrz.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtcdxtjcvu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtvjlzffuy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtywtnssbr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtczmiwswf.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtqeafdbvu.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozicfztg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtehjnfahm.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtssykgkil.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtvibcuyku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtmwtizukf.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtwaldotkh.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtzwmuaatt.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbuphfusd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gthakkjatx.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtautayoib.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtkqhnqgsj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtlghqjjml.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfjtetfrw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtvmqcwwjz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjjwuqku.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtwzqaaaut.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtkwxgfowo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtentbkrii.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtroginrdp.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gttdjduybm.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtjiiualbh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtgvtbuavf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtpeohnvqp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtvmrojnhd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtnnjelahi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtzufoklks.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtrxdxkxon.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtnvofmwbo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtpwlcypeq.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtyeuicolc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtyvlzjgdq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtcpbhoalq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtnqgzuwup.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gttdxbegxe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gteqwevuyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gttmxqcfmt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtkxapsopm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtrtuqiuhg.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtgavwnzbn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtauuhamwh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gthjhakpyf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtdstsqiks.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gttduzilsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtekqixnmo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtbltvlfjh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnlelydlx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtriqypudt.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtmxjwqpvm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gttqcvvzed.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtzgmgvfra.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtcqsguhju.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtqeykqids.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtvnwwovxw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtalxmwdiv.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtwhyommlz.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyzgasbx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtomwpedqw.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtssmpfwjd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfzoxkyls.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtfwghxiwb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtjrqzvcmf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtlzdzcdvi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtbanlnaud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtmwnudxcf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtszgrwtgc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtueosshtq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtvtcpwkjk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtfpsqytyr.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtejmmqmfb.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtzhwqcpww.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtokneozxy.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtpnkirfkp.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtvxbgprvl.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtzjzxadsy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtwbfjghnx.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtyytxhbom.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gttljvdclz.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtgirbogcb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtwzykzmdc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtseejcmvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtzvwibdwg.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gthjilfthi.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtljxcbgss.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtlhunkoru.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtztecuvot.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtztyaprfh.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtgyyeyeza.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtgzcpsrek.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtygwtbkye.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtovsccsar.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtemxejsag.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtymqnrgja.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgakdwckv.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtdakjpiam.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtxtwnhvzm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtxcrnubmh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtbxdiylow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtnzjbxhct.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtqvkcukom.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtvfgiwzzt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtqqkyfjdo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtysedeqfp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtubzwwjfq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtalresiqt.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gteuohxorm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtlnbohevz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtaqkgebgg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtkfczzjbb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtygubkdkr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtzufnvocj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtoadeeiot.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwazrczns.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtdtmwdhtq.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnwrbopc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtpfzrbeod.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtpwkkvkgg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtviddtzty.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtljgczgpr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtmuykrepo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gttluvimtw.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtottwsios.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtyzrstbic.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtrakwqjys.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtabsbbkiw.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtdasgkori.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtrqzsigha.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtfesiqssz.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtmotnerpx.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtrchrhyud.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizkwuuxe.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtowdahgdb.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gtnpurrajh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtdsbxbtme.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtvgixbjis.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtykbtzizg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtyvbijyma.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtihtfhory.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtvcqzvjqk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtacmxbyht.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtdkbuuxfi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtogzametm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtbhyibjrg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtdfwdoxmq.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtijwzszam.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtfclfqlbe.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtnobfmucl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gthjpluuzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtjwkgavjr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtluwffnuo.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasdvwjyj.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gttqtxkbrm.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtiytiqfvs.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gticgerxmu.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtctzwpyzc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtzvpkwxic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtyhoypsjx.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtysqwwhlx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtwhznyonp.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtijmryfex.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gthyhdgirh.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtmoiyzagy.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfemafphu.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtjewsduca.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtqblmgptk.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtkzzvzjdg.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkqxjuyi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtdcnujdme.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtgngsvqjz.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtvdlndqse.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtkunukbbv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtzopmtusk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtlxuehlsa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtfshfdngj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtyzzckqkm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtgubmnilf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtslqjksym.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtxuuzgcma.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtlwkmkhir.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtluehgnvf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtveauiizt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzkwwrppw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtlvwzqnmn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtubgsecol.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtvnrrnmtz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtynihksha.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtjmmctmwm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gthornbytf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtlbwnyzjw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtgmqkwiob.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtqnbfcjho.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtgeurlfqx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtepramlee.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjqedtfy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtrdtvzgik.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtdlbvhqoa.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtalfudtgb.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtdsfngqrp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtpafihfve.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtluuauonm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtseripqsp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtcbsapbaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtbiisjpsg.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtxdmqdtre.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtzyrusrvo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtccmyforr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gttmyuqgsp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtmqiqrumj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtpsrvlyvs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvnnzvxfv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtcilnjwdd.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtgqywvoxm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtixoxbqhz.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpiopeiz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqvslzgv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtwdcqksbi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtdrtnijvr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtlbijeenw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gttogldyhk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtzzstjpui.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtdwokeraq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrizdiqpr.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gthfnlnjfv.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gterhvhigy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtfkbhnfol.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtbelmripv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtuwalobpg.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtyvhnkpth.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gthnvnyivt.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtifyrlhqq.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtmvrrmyhi.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtkjwquuks.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtzkcbnaaw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtudyvhmmx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtwwsnajhn.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtkcrdmkth.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtgjaelsdu.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtgptpynlk.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtogpafywi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gttwxoreml.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtpcevxmsn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtwqigkvev.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxmfbvgap.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtuimsdtur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtwkavzdfg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtaggjcakv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtdwbxlkmn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gthfxqcbwv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gticznxnwc.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gthtkpssyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtfugugruv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtuwihpvef.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtomqbvork.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtpddgxjbs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtrpvihkpm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutegqhil.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtjymothcd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtnhvwhthb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqdxslfgq.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtbksyfonf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuxeucbtf.html


<!-- 参考信息 -->