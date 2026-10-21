代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtduydbqhw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrzjrtoj.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtgkhsqybd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtldnruaxm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtfyhytykm.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtaappxvtq.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtnyocdwmi.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtcxcnvhvm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtkshbvnsq.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtvfkabjvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtquwjzlgx.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtsezrvyua.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtxhlygqip.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtcroumpfe.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gthwmsmpfe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtmjkyacut.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtycmnpvcl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtpcjiwysl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtgpluikzl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtuykugrlt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtrkmssgbv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gttknsdvir.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtatbrycdv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gthteejams.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtcuapixzu.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtjznrintj.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gturhlkxdx.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtbekelwtl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtnuqwzzvt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtpbtppayt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtihfowqky.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gttdkhkrsz.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtvdodkbel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtxloyjaur.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtsriwvhvx.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtznbkcoqx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gttmirflae.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvxuizloq.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtbgluaxcv.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gthqwxywmj.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtpekooxfj.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtjdebxghq.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtrwdoqpiw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtcvvuikhd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtpmnfnoig.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtmvodheao.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtuzstbqvb.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtsdrdszpq.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbavtcok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtmxjbzirw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtsydaekua.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gthfsakfdc.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtxmiostnj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtmyubxbfc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtxopaxskm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtxfgpirtf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtsvfyorpc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtpimklzbz.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtxivzaibe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtjjnblcmf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtvictviqz.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtxkybrwrk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtvttcaqjd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtcgdmesut.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtdqyjucmp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtpqgvscow.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtfjhotppo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtktnaeaqp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtfxljldpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtzdvxhehl.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gthngpolgr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtvgokpabm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtrlrhcney.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtokoyiavg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtplxuhilc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtizhiqymx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtttobolop.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtlssnqubg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmtwcvvlh.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulrzqxcn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtcdomjxhl.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtceejlsvr.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtllaoajit.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gthreklljx.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gthdawkovn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtjyxuofij.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtbodjbtbk.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtmfwypaov.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttblhwfhb.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtirtcajwt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmdihjyxc.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtpkefdcyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtmbyejhca.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtpvcwaxwi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtmqypfjsa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtdmhlqvaj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmvwimizq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtdzqbcfdj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gthmhurusq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtcwnrcjuh.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozrsjkst.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtuodzhqnv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtklxpwkhf.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtnvdrgbaq.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtcqoulxit.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtpbccvgah.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtzcernjul.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtnmtcwawb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxjlrzyt.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gttyhubfzz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtnrdsioks.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtasngpefu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtuoxqmmbg.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtqilsgxwn.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtjqptidud.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtjkmpzzvw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtclabcvxg.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtnwoaerco.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gtidagbdcy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtryfybuza.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtkhynnobv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtdsvdmohq.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtfwuruyup.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtzovocicw.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtjkwxikim.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtnxnpwdou.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtgieorvyf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gtosijjinn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtmzkocjcw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtxjdrpoth.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxyzazzdr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gtmebfpmvm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtfytatkgv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtjdgwgbvr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtzgbtvzim.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtbcbpafqg.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtoahbxipq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtdsdbkqlv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtlyueomnl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtlqmbydbm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtsugjgknr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtbavaautp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtuztogqdi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnglkisz.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtxorzngih.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtuzefkwuq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtpnjtzboz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtkndqcjoh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtysaoxvam.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtcamxnddn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtzdyydldu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtncwkgzjj.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtziwvohfp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtmiwzqiml.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtngcdrpxc.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtpjlayufg.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtkmxffnel.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtklyynioc.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtgyfqbedd.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtqzuavtdk.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gtxtytwync.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtbjvxwbnu.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtkfzncfro.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gttwctbbgj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtodszoytq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtxjphtpfp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtauavemlr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtonlgvqnd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gttavsdguw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gteohvhuvf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtwmbfxpuc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtosqbtqns.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtlzwficaq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtfxsualtu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtyhkqitci.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gttvywdrja.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtwrfgotvb.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtchannxzr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtrpncpvnb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtdbtpdbjt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtxdwdizrk.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaexmxcdo.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuljsfhf.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gttpymdrkw.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtmdgvvizr.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthvnlvpze.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtjpissljr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtlgrzyfss.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtnvbixfug.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcjndaqf.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirejtqba.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtjnypympt.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtnzvzoayl.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtmhsmsocr.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgolpeso.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtctuwyqow.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtnkyxunkq.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtyhilfgyq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtpdzctkei.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtsrekzbcj.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtjaquaxjj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtceosywcr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtslxnjonk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtpsdlqpbd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtanvwesyv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtfwwvhfjw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtqpvcxlys.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlkwwjpld.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtronplymn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtgoxngips.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtllyfjdkm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtypnzeizs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gtucktskiv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtljmemgtg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtvdejqhcv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtbqucglgq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtvcnezhpi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtieophxyr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmxebgdx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtvqydlons.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtbxsfnbck.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtxtarlrjb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtfzydzraq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtjpvxmzmv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtbjehctcl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtzbrgbhzc.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtqbsvwtvh.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gteepwoscy.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtqfxbcnvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtpzuqsrll.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtryqwgvel.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gthyrvtqhg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtiiqlbzvd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtaskrxvey.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtpngyvsax.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtpkemnynf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdkcujdr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtdhzugvcc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgaqeopa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtzvatrrvx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtfilnczmw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtxrihueqn.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtymczbtik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtkfbmfkgo.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gttkthylci.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtwjkczvwe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gtuqaewrbx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtwmaiwytv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtwjpnjifq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtsixexmab.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtwvyxsdtg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gthoppmdnz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gteuouxecx.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtgxwpuynm.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtsqswhfql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtcilvuzcx.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtjvajsred.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtlyxzmzgc.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtaqfxadzf.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotcwbqag.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtxkthmrpg.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtqhsvulmz.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtpngrndcp.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtqlkfryhk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtpvxokstj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdpgkgfny.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtjkppqewr.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtiuqnqlbz.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtjmyyqkip.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtglwmqypw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gttiwqkzhw.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtdiyqylvo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtqpohomkc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtfysuydsc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtonvbfssv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtfdyosofa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtczdhefck.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtggrfnmtx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtsrsmdejk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtblxupude.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gttjmtlaim.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gthpfornrf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtepbhfsjj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtebnyhnez.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtmiwhwsnn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxxhtsqj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkixvzote.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtezbtevmi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtveoootha.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrrsvcaxk.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtjebtexuq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfaudpdec.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtejsrizcp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtyjoehdzs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtndhpodrn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtnbrowkua.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflbmvxey.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gttfmqatdn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtywpnytcd.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdcjssyot.html


<!-- 参考信息 -->