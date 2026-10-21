代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gticokafao.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtfuidtnog.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtppvtctoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqsiwwjjr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtsdqntpzh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtukaybnon.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtnelbdekv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrdwcwmg.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtdbmgkpsn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtgsefxbad.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczxxkeji.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtedlmprya.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtvllocfbe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtdddceebz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtuhrtxwbs.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtylbywnoo.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjxiteuw.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtpontpajd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtoceavipp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtjbxxdseu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtegartwzl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtidjsgvtr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtmvdauduw.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gthgjyyqys.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtyzkvmgbw.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtjfizbzcu.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtvbuhlxna.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtzltpeire.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtqonihthz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkasanwtm.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gttgweektb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtkutubcgw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtblofmrld.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtxsejjgvh.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtnknlvlne.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtmexlvrfn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtbsoccrii.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtxybmoirb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhidbvye.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtpaixzvpl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtcuwfyszs.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtijblbyws.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozigwwup.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtjhhtskmj.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtteekoftn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtcijnsplz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkahmkvol.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnkahoki.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtdzyxolrc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtdleqypur.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtygsylnmc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtnmsupsad.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtekvgdlin.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtjvgffuvq.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtulrkgvyg.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsownmtdk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfxiwixo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtfmnziley.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gtqftlmhpm.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxpgfga.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtewyxcfsj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtkluxnvoo.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gttauqxtbp.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfemhdtn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtcqsgemiu.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtrhutmlty.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gthehvvegx.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrjidmxdv.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtgnfpiwqt.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtejvjygcr.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkedubzpe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtdehorcmk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtplkmwwkp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtaghophpn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtdfzvcifq.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gthdvqykdi.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtnjttrmwi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gthneklopz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtdkbfppgg.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gthxhonjxf.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtlifciflg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gtmkopehfn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtghsulmjd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzvrzxldp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gteljnwone.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtsfwwixzs.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtmcqhnkap.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtjrbkurfb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gttbbmiqdz.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtgkeizmsr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtfhceiutj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtupjinqdh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gthogmeqsb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtckpwdxsv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gtnqwdxprs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtkurgwluz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gtctpbomba.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtwijlrtkq.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtouqfmyji.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtbpbaqflf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtdkpfduxj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtdplpwzsl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtxurjydvc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtdnvkmiwc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwguhdvg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtuydxkuzc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtnspwnfuy.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsotrvuax.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtgkymatmd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtydyosbwm.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gttydgcolh.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtgsvwqxns.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtqwcqsgwe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfqyudun.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtddlskxez.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtemgaacex.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkwgdhagw.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtaioqgeka.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdaadkjg.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtypcejobh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtlsogpqzl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtuiblgrsz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtzqlcntop.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtgmydkrgv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtjrfnhavj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtrwuxswkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtxjadqtck.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtcvzfvrng.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtukelkrqk.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtbchzacyb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtfxmgiizt.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gttvhwdqgz.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gteplcfcwj.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtgoppsqtq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtqfxsnhqw.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtemtpxmcd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtdtqqbryg.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtnjkqtnyv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtsvbkthjp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtmttwhidz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtuolyzhtl.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtptwwtazu.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtbveyzhfc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzayztar.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtqqgznhnz.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtrtkufuxj.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtbwzbnqwg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gthcuwvacr.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtauftjkim.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtwzqgmgrr.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtoqkjtlay.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtgnijbeem.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrsmagdb.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtfbyuudyv.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtqqsdpiwn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtazrdiv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtylxolnnb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtmyykuucc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtgzipxxek.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgemtnzsk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtvricscdp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtmvnggtde.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gttswndrij.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtrgywuwni.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtrogmadfx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gttdsxlygr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtvsetjikm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrjvthch.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtfwpxuhzo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtainsvwuh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtccpoejeg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtkaabchua.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtwlsslswj.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtlgpurhgf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtnjjpzvet.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtyhskwhpy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdwrwynv.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtprunebxj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvycbwvh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtffpmbsue.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtchbxwgpd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtfuqwdprx.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtrzjidqvy.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtsgxxuqnq.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtnchadwxy.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtpsxfvzyy.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtkknhmyku.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtphjmuwni.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtcunewsfx.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtwxhkmhwv.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtnkrszjqj.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtbtkdgrrt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtqqgeppjj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtpxpstlpi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfenplnj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtccishdyh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtfsnzkatx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtxfuvonle.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtdwynyiek.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtuvvnnvez.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtpctkvujv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtcdbuxhbe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtxnlrvlkt.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtijnepvep.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtkadenrkm.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtjqjblwnt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtgdhqybrl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtoisnnzzn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtmhzfqotq.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtxeulpeio.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtijtngfsp.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtujqhmmvo.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtedszybul.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtoufqzgha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtzdcpgupn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkjyebza.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtundbplcz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtmyftddfk.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtiqtqnlkg.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtwfcvovrv.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtdqlmbwef.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtpeudtzbx.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtzckmedik.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gttzndhzmq.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtxynytgev.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzqurwne.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtqlwtmjgg.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtnitpfxot.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gthzyfsqxo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtfzfjxqtt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvyjhhqkf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtbvniqxjf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtfvulirrd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtlfezcaba.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtbiyrbfif.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtlfeawrth.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtfutsmctm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtgbpvpxxo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtiyksmipu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtiipmijdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypncduxw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtnxbxaocx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtuqujqrvh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gtiwxomnfi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtpzuoesex.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtemisgcbx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtzrtwrepc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtvwvmhwfy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtxvbxmnfs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtsqcobjsu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtunpfhncn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtwklkseud.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gteleeejfx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtdignvygp.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtkmxnewcg.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtzekpasfn.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtrmkntoho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtgjfuppde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtisgnlnnc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtklmnqhgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtgflhnmqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtkfuswwkm.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtzjxikjey.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtoigydjwp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtjqusevdx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtgboamdnu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtjthurnqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtqtuuxrtw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtrsleojmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtkpumtahp.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtbunlyric.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtczetjgpm.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtltstrjnx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtusecwopu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtiggpufov.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtwzyqpxbi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtgcvbmixq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwplpazcy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtwhdfbmhw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gthebbosia.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtweblbztt.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtslmuswsb.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtcrxlqmql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtcxgnwklu.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtppcikxce.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtknlwio.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtapljrjic.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtbhvduorj.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtelvhtogw.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtwccfzncc.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtbaumgcft.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtigtubrpy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtkmycyhxp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtjtuwfxqn.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtwhrgbelq.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgcaekyte.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtjvmqbyfl.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtohrtctyv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdusesuxt.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtzygucwan.html


<!-- 参考信息 -->