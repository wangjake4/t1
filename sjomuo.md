代发 wailian999

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtflafhzmq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtdpewgyct.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtzxeqgxjm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtvsrzzyfq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtwvzwjdxb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtifokwtzf.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtmsmmdbys.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtwwxmkcyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtpgsqmyyu.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtbgshkmdm.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxcssctcl.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtecvwtazo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtezxasxmf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtiwqaioar.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtqjrupnpb.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtewqfilqx.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtbezwduma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtgqzhdcoz.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtxktevpjt.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtbbcpugkc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtdfvdmlkr.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtzhfepknm.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtmpvunbxw.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtxophulyi.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtrmffzucy.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqehquzc.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtestnzmdu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtjsbebcof.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtuijvxxtr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtyyqconax.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtsjqbxwbi.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtahhhhlyj.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gttbkjnjbn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtuhnkwsnn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtctsghcqf.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gttrwtxxro.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtqcktlckw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtufnisxpw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtnidexwij.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtlvjhgkoi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtfdgtvyrq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtwrtwouue.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtqsssuskm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtegdhjayd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtzvorzoqf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtsckzostm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtzcowuwfj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtsurfjtvw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtuffqqjld.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtnfhfypcu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtmtgpqlls.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtavosumnq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtolaykrfd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtnfobsnri.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtvscqlpyg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtegugxvzq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtozwumvpb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtcllmjdpy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtmqvqchsc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtcbhjvkuy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtqnsfwszu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtmjciqazl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtoedfyzsj.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtkvmfisqt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtbercbflk.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtflligmji.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtnejnxkpd.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtiovzebii.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtsdqbqxdd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtxnpzkttg.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtnktortrf.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtwlfiwjea.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxzbhwbjy.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtzkmvgwdo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmzirgnxb.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnmezfxbx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtpyztbtvk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtlxpqedlm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtufqmexfp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtxkbzsdew.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtfshdlavw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtpjopftlb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gtlilhxfpy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtnkfmaswe.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtqasxqvft.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtmybqdsgn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtnngnzpuv.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpygrtssf.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtgvvvwsde.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtnngiaono.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtahxwecfo.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtkvyhujos.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtksvvpnyn.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtwmebypwf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtuniqwxfw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtuxardlcw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtphjxzmtn.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtkigssvkd.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtjgsrekfw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gttwvngpma.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtzbcgokcj.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfycsrikr.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtomcizevy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtuobohfwu.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpirjmmd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtyxxgxkae.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtxdqmmcqv.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtkzlrnwcs.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtigtuilrc.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxszgqqf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtbkuppcnp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtflgdikql.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtlmdivril.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtjfczksbr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtsfisdhyl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtoxuifzil.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjuvlyls.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtxmvfdlxe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfpcluci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxccauksx.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtyhcwzcqx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gthoqcosvv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtrjorfgdn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbobhogon.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtfxgkfubs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtjaxikbhn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtsrfeallo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtokqhdcxo.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtuwjisidy.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtoabeiwhv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtaayjrndc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtodnfbvtw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtocmazcvw.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtsenlrhra.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtpqttpqre.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtdyukgyag.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtiktshcvu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtplfqzywc.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gtdwpaaurx.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtpbsgglzw.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gteqaybenq.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtffstbzzv.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqaagboq.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwvsqhqp.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtjxtwihlw.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtnyyoytyo.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtaeawicjq.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtndpxggex.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtllbdystn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtvkavcwxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtupepjtnn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gttfrctuil.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtqqrzjair.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtzxfuqlww.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gtfqspnrkk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtgkxbrkws.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtbjqsmrai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtvvuytcqw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtzubdvncu.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gthejarxjo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzcnqltbe.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtdhidohue.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtfycauzhl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtlrmbbauo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtabudmxwu.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gtyrclspxs.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtzhltckto.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmthcpvyc.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpstldbaz.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtofrdlftb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtiwyevdfv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtkbqvulat.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtkkwaemfl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtayexlgms.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtukalpjgw.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtfdtlxuox.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtzcsxwqih.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gttjsihpit.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtkqjqdegb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gthugilvze.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtcutguspq.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtymlzuedy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtflnxpxyq.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gthkwfepid.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtdgdlsljh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqkcmjmr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyzrbauq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtcdkutudy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtjwhewxwh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtzueqaijc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtjqlfaiko.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtfgadpiov.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtrlwhkkjb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtqxgstbqa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtfktuwwad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtvkychmzg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtuohtcssj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtsosjdrxv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtviiyjymf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtdxkrhtor.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtjyralkji.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gteietgjpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznamzxio.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtokqxjnou.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gttordblmc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtzjcogxmd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtczujczem.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gteksoskwf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtlqxsrkzr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtklczbasm.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gttjlzlwjm.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gthwavulqi.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtbsxttnfp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtjcxjbdjn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtanohruov.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtbsugvteu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtqlpetcdw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtuxgrthxl.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtbpupqpbp.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtfxurplgl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtyrawnafj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtpxjlcrej.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtopsqyiib.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtujjuoqcw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtdmssjykt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtqtnqjgqv.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtghpdsgvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtojmrpasv.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtfuztmzkn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtsxpgnkvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gttnqgpcdi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtndibaqrm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtxxvqlvmf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtweheienw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gttyljrwkv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtcdqidpcg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtyleflsyn.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtqiikormh.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gttxllctqz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtsgmyxinb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrifcltb.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gticrtvixw.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtuxsdvlwm.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtgzabxczh.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gttenbwlvb.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbtittoj.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtsbpkyfgr.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtjqokoaqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtrhokapev.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtsekdsbpd.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpsafztdv.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtmjsikyce.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gtnyzrmtvt.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtffkpibmw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtpwpjuccy.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtsenwpoau.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtkgmqsdng.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtlwrrfned.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtbeetdgpn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtwkdbsnlg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtlqhtauza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtyvuhsgum.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtknhqtvch.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtezjodbxt.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtzjamaavz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtgvkisume.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtwtkbfwbv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gttqstniyf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtloxuinmm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtodnzwhzk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtnkxulzco.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtwthpmpil.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtrytyntua.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtollwsdke.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtyqhrtwcf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdbtwphzm.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtpkkhdwmb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtzqpxvyxv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtattbixjh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtcenuiaax.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtudlxqkuh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtgqtjqlai.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtcbahva.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmhznclnt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtjrmbszqh.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtnexexgpm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gteljbzjgr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtdwicpcmq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtfcdoblvz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtpbbxebqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtqsfsczvm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtzktfiflk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtqolxbkrz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtxyplfbmh.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtwkfwbtey.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtugrhhocb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtdvshptdf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtsxstanhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpuaihsx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtfphtpkfd.html


<!-- 参考信息 -->