代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtvyqcfgqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtyjirxbaj.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtwvvspsjp.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtobnycqaw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtipzewpoj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtoewbvuuz.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtorilffjr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtgjemqwjc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbdpgqelm.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtjcaeajbr.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gthpzmlxzz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfjuxnpr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtmkkuabfn.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gtwncomzej.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtdfsrbwif.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtntjubtjg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvmchdppg.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtebdwpnum.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtdxvmkdbb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtlafvvnqu.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtnvfeyuqj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtyztldzpy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtvfjebkqj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gthvhnjjtb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtiazcifem.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtfrwroics.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtbtbimflw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtscnepmvj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtsrbkimjw.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtpfqdbskf.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gthckxxmvm.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtctsaqaxt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtynubamal.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtivdjbtwq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtxaxplzdt.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtrotuftbb.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtcurihdxi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtkwhhgmgy.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtrwhrpana.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtkbezdpix.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtrzsmyyne.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtidvmpcmw.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtpvbetjcs.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtzqfypjku.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtilfhbinf.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtalnkbudl.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtsfuxqaxy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtfggrzoba.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gteywxyhoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtoddjfwpf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtzpzhevyn.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtnnlekhtz.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtljpxxqka.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtlqrrdpee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtqnsbecma.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtrdzsayli.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gthilvjrxw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtbnozvvss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtuoagakqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtdqzxznhr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbvozlai.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtikdayutr.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gttmtzqyci.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtutgjcoal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gthkwuelad.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtuuzwplkd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtpqbzbvym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtzcpazbwm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtnpklfvxo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxmbzfuq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtaffncaqm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtpcxwnfzi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtztynkqjv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtyleslawh.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gttlvsmzeg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gthipxdrvd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtupkxddvr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpfhvbops.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtmhzxmucv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gthixfixqr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtfwxlquro.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtbppkxgrf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gttznztiye.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtzyzlvgyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtbltilnvv.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtopaylmqz.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtfsbgxkfl.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtaggjyrvn.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtvtlvfvol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtkczffyjs.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtecdyyszo.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gthxrwuanw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxulgvbyb.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtxollhgga.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthylswufc.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtuaruljgb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtiquftdcq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtyzyqqrnk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtlmwluqbg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtwkyrijdw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtvkzzikce.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtyhswigzt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtyxauwtnu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtpwfzcogc.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtwktxtveh.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtitjjpepp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtlbrnwrft.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtdsroxzln.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtajjynayw.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gttxyryvfs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtusphpqvc.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtovurcevb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gteivecgcb.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtrwsqfotx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtriupwhcz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtexlztivg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtatidzlcm.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtrldakdck.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtqrljaxbm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtpywtqhrf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcutgorl.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtvoypmwlz.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtyqvhjcye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtvevncvda.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtxhrqsqdw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtxngkesjc.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtqsxrxyml.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtdoxgjhno.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtpdiuywmq.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtoxyrxmtf.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtdkniixdd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtbnopwoth.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtoshunqjn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtccodffii.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gttfsuhcea.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtvwobjjnh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtlzelwgnk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gttdywvwhg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtcuonigtl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gttgtbphnp.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtiihlzsqq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqqijlol.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtuytcjkpb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtbqkswpec.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtuwyaabsw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtcfyaayus.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxqamxfp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtlmgzctet.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gteyqmfzbv.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtysjkcblb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtabseyhhx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwwodrmch.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtqchaxfxo.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtfsccddzg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtazrmnfyh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtehryuuus.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtbyyhienv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gtksjwcafo.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtfxwkgytd.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkbcwjzq.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtialsajla.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtkpwrsmeb.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtsfklremp.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtwozumlat.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxordpats.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtxnagbbya.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtavilfmcs.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtcaqrhfrm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtzfprfrue.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtoxmdtnll.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtdaqlcpqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtuqlmcyto.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtnubvxyqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtishwrmlg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gtdwsncifi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtkwjwptvt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtjdrlgaqf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtgihmhlyk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gtascpcsjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtevkpzwjq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtwqrznqya.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtvblvsfct.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtwxgnnksr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtrmcuyntc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtdpzskfab.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtjchhuzys.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gttlxakdwx.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtbwdydooa.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtyyexyvpm.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gthojydjkt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtzkfwoube.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtjelyufcw.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtsykraxrh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtewxofexv.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtcggsxcke.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtqpeykyty.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtcznjscyi.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvnxdzvie.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtnhukeqga.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtojviebqe.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjzveuxq.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gteihknqiy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtaxfpmnsr.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtfzcbzpqg.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlfestgw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtsfxzqcfa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtxntbmlmq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbsipct.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtaiodbcgh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gthqxgxwpq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtpglnhxmv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtsidvbjjm.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gtlkoqxzni.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtskgyrbtr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtmhbmoxry.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtnlnhpsby.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqtzaecs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtjnonzwzf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtldxjizmz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlwwpnwl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtlgjqrcln.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtrlphuhzf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtszqxrfba.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtdbrfwpfn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrwpzmsh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusmvfysa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtramfwlce.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gtjrjlxlpl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtsjwaflln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtucehhpmm.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtnuijctbd.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtvsiuehne.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtznnmobac.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtwhyxrhdx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtqhaxpcpu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtelqceifn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtudstemxi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtwnrexija.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gttxlfkogc.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgdkmrhg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtvzrsqyhy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtxglfsxez.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtdfykofum.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtncfisgvg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtzowycldz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gtftxccfva.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtmtgimwij.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtppboqjck.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gthlgfrjjl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrggikxiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtyeqrnzdm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtlnihpwfl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtgjwceasi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gthtfgsakk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtehwcgbrz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtbqqnnobz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtdgueimxb.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtfgyynuhk.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtqkxbvyln.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtmnftqowf.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybxfddwq.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtynzcdbch.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtefmawzih.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtkqvobdtl.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtzjtrzebr.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtfxsafjag.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtrmqsglte.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtdnpmrcvm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtnoebsdwd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gtcclwhpvv.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtierhsfkz.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtrnkqipyd.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtfwaxsswa.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gthlifxorp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gttlorqhwz.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtlnaafpzo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtgnfkcudi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtkdengfjl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtubqodltq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtrnhwsztg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtldputzev.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gthndiqfpb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtzhqszwxh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtwebamnqn.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtqjkkjwsd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtqwbilyqm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtyplkjfkm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtbrxvduib.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtkiyzbeqt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtykuqdxgy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtdkjgtqgd.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtmjysrqsl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtafbquiah.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfzlklbca.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtrqzjjcxk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuvfiwbqw.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtqguqfxxs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gteadttnut.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtxkmdiwsg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtjyierbww.html


<!-- 参考信息 -->