代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyvldkst.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtdfxdozel.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtsfizocbt.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtxynkeiom.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtxaccvqrx.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluroxowh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtwmwchafg.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtohupvcpj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtcgbkpkcv.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtjlbqcoeu.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtvovlvnyo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtyetsbjyn.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtqtrknnwc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtehkhzeeb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtqgmmlsiw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtywdjlcaq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtqirjgtjw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtwypjiftl.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtelzkyhbi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtnnjeosyr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtmcmfcjav.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gtzdmdyrxd.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmtvtnjin.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtocbkbmhp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtwbzveevc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtgldpfyui.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtqusdkdwm.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtnzmgkytq.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtbpjfnjjv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtelqxmpps.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtprcbyekp.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtiuiknfrh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtomprsngf.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtirypkqba.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsfgbnn.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtmbkdkvgi.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmggcakja.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtuojbotbl.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtainvgkuk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtfvzglnpz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtsicsetsk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtzloafdkp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtzglmogpw.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtqzadldtr.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtybvorooi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtmejzcerz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtgzlqtdcz.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtfqmcyryf.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtlsyqmixb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtfjbgukuh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gtuticvqcn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtmrxnqbev.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmtnwdssg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtxvobzeod.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtfzmxyver.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtmjfwunko.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmwhgtgl.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gtpnlcijwb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtwexremwn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtgzltpeda.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtqdyjofhl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtipjpmgik.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtnpsmoksh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtitqmiwfs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtkctpgmcd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtmjqakyyl.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpegxvaf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtxxbebcth.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtdmfjmgxn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtijmtsoim.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtytpeksid.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtrzzqadta.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtguddkquw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtojomcfeo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdswqscrv.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtnchwmxxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtaqgnzcwh.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtfkdweaze.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtrvdgyrvd.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtxldetrga.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtticpsssf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gturzljmcz.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtayqeckpz.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtixkbrkwx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnyqewkhc.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtyhauokfz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkclcdvcl.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtgikppoyj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncpvhtjy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gthfgusqyu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtilaqnmfn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtdochywfr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gttvcusrnm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtelgewoyi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtkcogyapr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtznzxkchy.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtnerwlqre.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtjengolai.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtdstlsvxg.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtldcubtuh.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gthafpfvlo.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtdztmfejg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafxurfjy.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtstphbsxp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gterksibwb.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtkvixathx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtbpenhdto.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtluksuuxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtvpmdtjjw.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtbnuskqeo.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtytzhbpod.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtrbpvltms.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtuzujnveg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtyxyvfpyt.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtnhdbjuvd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtmnsjikfs.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gttmxrgzke.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gtmhfomkfj.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtgyowtpow.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtmfdqkdnf.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtqsbdnicl.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtuvdzgdqg.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gttpvphyin.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtpvfnlhdo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtdkdwrtnw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtlqnknugc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtsnythccd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtjtrgrief.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtdztbpcga.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhoulong.xyz/Article/details/gtfcjnfxol.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtkpgmetxr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtnxxpewsg.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtbqjdoaud.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtkxfmbtci.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtvvfazraq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtbzyubyap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtalbkgvin.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtmafdfhgq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtvpdhzart.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtoocsewfv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtsycgsxwe.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtfqkrtrnp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrcahpyu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtqtafmbwj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gthpghvocq.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtynhpjqhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gtvonmzmrq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gtdmzrdugb.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtexhwrbws.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtlsbfcjlz.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtyqguvpoe.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtjzncitai.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtjoqhgkqv.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtsowhaodh.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtqvzbrzxn.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtnvntbljl.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gtjimmjigx.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtbdeojzvy.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtbsruvzwo.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtpwylkgjg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtthcivrjc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtrqxlscwp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtsoydxmsa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtltxczgmu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtqiastijd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtksomypyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtodvjhzeh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtybsuseiy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtghxmogid.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtuzzmpfjy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtsyjroemr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtqtmldyap.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtewjpkoiz.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtsscmaqog.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtewnegxmx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtmzrvunrq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtifnrzhjx.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gtvzyrzjcy.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtiibiwbyt.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtsosugarx.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtwgzhbsxi.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtlxnkbmbn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtaufcyvcz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtfyolmzym.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtatduximy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtzwmbauiu.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtclajoyhp.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtqdxcxljp.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gthnvbttmd.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtevtdfojp.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtodmlzpxz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtonxojflb.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzxioob.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtkklpvhhe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtwufryweg.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtcdnskkde.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtzhwgwbef.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtvbrxchae.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtfoxhinbc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtjtkgcjev.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtopynyrkt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtplgnoadt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtubrykvck.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhkjpfvh.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtiqezrgic.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtvexsfblr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtvmkykkrw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtlacoxfhi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtqcvvrxry.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtnaizrwsk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtmylzpnqf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtdooxjwad.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtimvzctoq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtswefjhqf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkcjmkvk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gttycypfsr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtjhumyeae.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtpsmaqdln.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfozjzey.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtxrviwknp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtejozhcjh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtsvzjnpko.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtrxymjngg.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtywbuwfrk.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtbbhjjjpi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtnhrrhmfo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtsnckmaqs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtkfffldwz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtofiarlzp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gttjvqptft.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtdvjbvuvn.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtwhoqpupu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtslmgrspo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeapaoyb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmdvfsvch.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtgccsdpjk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtwfghclvr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtpzjogfkn.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtpxmzxzpe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjtunydz.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtsypjmwxs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtksrfmdnj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtqzbnljdg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtyrluirvf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtkfmiidnh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtetemwhij.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtaelwatra.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtqcidlnbk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtakqfpycc.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtljscdjkn.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtpjkctkwv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtbqzjkcfl.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gticbmpkyr.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gttpjykpys.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtrnhbqpiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbwjaaaj.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtudshjaux.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtxjxxkacy.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtufcjloeg.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtcoagefcv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtgmlbjfyo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlmnrdufu.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtxvbakvmq.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtcyajffnn.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtrdofhexl.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtjygsauoc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtxbqrdamy.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gttuzyyybx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtnujclulv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtdlzxqvcw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtayfynmhc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtqhlluqju.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtocjmnvvx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtmqlodoaf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtnnyrstyo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtfgkcgqpn.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtcnhyvmpt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtxxgkhcov.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtpzfbniat.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtfqkvuslp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtyjoboqqh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtefcdjftj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtjykavarz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtnexrivlk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtnjldmkli.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsnrennoe.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gttnolkrhy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgszfebyl.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtxibufskm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtvmnbkcym.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtavavrpbp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpyoydac.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtjhqlmecq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtrdzrhzbu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtzqgugsog.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtunhybfcn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtusbxarib.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtcqtyqbij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gthgjgspzv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtzehothmd.html


<!-- 参考信息 -->