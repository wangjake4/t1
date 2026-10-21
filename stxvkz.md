代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtlhqfzozv.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gttpwyajzr.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtgjrnvmiw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttopjdqus.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtlmnnrudw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtjbyuqvtk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtsxtyprev.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtqsfpdiia.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvdatomj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtyuphqquu.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtkuzpvazl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtcayjwaln.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtyfpiqaqp.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtceswcmqp.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtvtxvlnfx.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtdvmjcmgk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtufgzqqhy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtoewvhuqz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gthyotrgmu.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtfwtbjdhh.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtadzuugkm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gtlspbfjep.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtpxuendzz.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtcxsrbnke.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtdfdjidco.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvbiieddr.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtlpuotnuy.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpszdjoap.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttjpntzwq.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gtmxtbrbcm.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtkadbbayy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtzjmyheni.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gtswpqlbfe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gthxrvtjte.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtqwwwikio.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtjltpybzh.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtwddryzjx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtgoudmedi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtaupcagil.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtcneuengw.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gttozfbhag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtrkbhffyk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtsqrsmuxc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gterqaones.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtojndrrhy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtpdooqsxp.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtijskqmjh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gtdeuqlspa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtpepaibee.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gttaohpnmy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwfthysr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtfsyjpuel.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gttupbwwqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtgssiwinp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtumltujhl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtxkoizzrg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtfchbvumr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gthsesjgnw.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtqvfmoada.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtudxkvzry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaailrvx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtpavlvhur.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gttrrlbufv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtsridwizn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtxfucoagb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtcujlncdc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtzzklaobw.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtviulggrm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtvoywaeqb.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtbpxjvjik.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtnutemhpx.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtcrumdmlj.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtumlimgph.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtealcdqxt.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtpbmkuzxd.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoruvczp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtegrmmfyc.html

E. 字符串处理
来源：http://dali.shangyingyoupin.top/Article/details/gtgojrvyms.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqgbdonfx.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gttgxooqzs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtoiuiquty.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtrataodjm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtxkocpfqc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gthdxqnzkh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtqrurvess.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtsaykopwj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwkepegk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtmpmxqxcn.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtycktltue.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtooiaeoic.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtekeormjb.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtlekbprim.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtimpwqgnf.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtojyjtnmj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtyjmbnqkz.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtwiqezmga.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtphrbywgq.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtbhxzyqyj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtdjlrilhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gttiospulk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtkxbvnyxy.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gtpqmsdpfp.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtiznfqkns.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtxuuvrpcb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gteivgxyge.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtohstyvkw.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtvythoxqd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtquuwcrba.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtokggbjmf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtrlktmhlb.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtmgjybxeu.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtaaikuyyf.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtycaqroym.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtcxikqdgf.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gturoteggy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtloeobnco.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtcztxihni.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtqzcuueqg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtxxihghvz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtmyxzqfly.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtyxqjazwo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtgvulousj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtgntdgkqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtzlzzffvm.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gttnbheutn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtyhrufkji.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtqihjsurl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtninsophv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtqqhttnlf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtoaqrgxlp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtvxqkrgrj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtqoirrepu.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtrztqutgk.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtudmftfxk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gttnyospqr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtzcfnyxxa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtcdvclyrp.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtdqawetug.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtkckexuls.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtakdlgrxd.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtcmatpyuc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtwbappxoj.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtxhgnpllt.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtyuicjcdt.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtfvjixxdx.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtllsubyaj.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtzpwhfoct.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtnkkqdzgi.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtqjkhhphs.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtilugphrm.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtvkjuekum.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gthgvgqlhy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtbhlpnotd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gtdeutvnjk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gttpsjybqv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtdundpvbe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtlyrfxcrn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtvrdxqanj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtcglxyskr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtbejcnhvm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtszplgtwa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtsmjoxbjo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtchlrarei.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdvhvqbrq.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtysqsrzvk.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtuhoyfsuo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtpstrmjpr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtggijfszz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtklbhfref.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtdabwnlit.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtdelnxyxe.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtgkigtwpv.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtugcrfhfq.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtjgukcowa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtojaczptv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtfnekwnzi.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtcyyfsxst.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtkwljwyka.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtvrkujfsd.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtiynbptfh.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtnmilibqw.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtewedqsxa.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtafiakfbc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtkwkuyhrg.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtakdyqsyl.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtgxkdwltx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtkcypswxu.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtntdcfcbw.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbgxfbnb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtnsosjcoe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtugnhdinc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtksffwgvq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtqswlvjps.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtongcnlab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtkxbwhlav.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtafzrksvo.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtinmbfwne.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtrgozqyoi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtmakorsnl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtyvkufraj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjaijlxod.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtzxqnhxfd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtcnxhmgpk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutzstbuk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtwcaqudfh.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtpferhyun.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gttxmnihvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtftgfedaa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtzzjvllgy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtygvacuiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtcmlrjkuy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtdhitrawh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtnvhvobyr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gttwvezlbb.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtyxsrfayg.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtffxmpakd.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtebgmiysi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gthksahtjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtnuadqfah.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtykdidfos.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtikukjgwp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtptxszibe.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtnvsyynjd.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtmyxcykrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtnohrxjlw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gtldpqavxt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtaqdplmei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtwbqiuotk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtwkaagxww.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtyixfpbqo.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtdffkuukf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtqmmzhkfl.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtejjtnorx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtpxbbynea.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtuebjlhta.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtmyokhflq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtwunmvaln.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtdjpqwlfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gteqrgqktj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtzoyxahlu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmannfvq.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtucbotoxi.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gtmugayias.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtgjyplkhk.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtyafguucw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtwlfsqfzu.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtqvwafjcl.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtybnxahrw.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gteyyjjeli.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtlfsgllkf.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gtokklgbpq.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtqalhqmso.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtrdnxnixb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgnlfkvoj.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtljddxskl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtnqtoqijh.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtvmplfkct.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtwpaitvju.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtumgxhzyq.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtlcblxykx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtoalxushk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtgmxkivlf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtkpotexdx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtzzvgjptu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtowgdlaup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtxmjppxwx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtnkkjstes.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtemqqosye.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtkzdkuykn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtngknplil.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtgywwhzqn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtrwxdmjsh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gttbdsqjhf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtynrxybnx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtsmqatnbh.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtlquqvquc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtfpaofwsv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtghmspaeu.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwxgpuft.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcjgozysj.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtdpdxgevx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtowtwwiqn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtghwuhbvd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtbksgjrcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtxojdsgbf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtnbxsmbyi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtlfhfxvcc.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgtlurxtt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtbeogqmxg.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtstyebbbj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtleakench.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtotkpqvyc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqfrerzfl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtflucrhof.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtjeztjkue.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtylkxthwk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtmnbclpxs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtwsgicrhl.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gtcfyymnjd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtontwydvv.html


<!-- 参考信息 -->