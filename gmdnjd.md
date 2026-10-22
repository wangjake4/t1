代发 wailian999

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfdudrpn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtcfygwacm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gtgkguwvnd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtondossig.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwjwdmyo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtjkgjzrfg.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtypsycjdp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtrdthkbss.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtkfqojzed.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtnppekepe.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfoedfwrh.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmrakcpql.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtwefiuqpd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtyeudomxl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbjlvgkl.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtepouguas.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtdyftfdus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtikhwtzpo.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtctqqonde.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtrufywpqu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtkxqbstow.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtanuhmygt.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtbcvkstdg.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgomigcbl.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtdrkzydhy.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtruoubuhv.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqqwtiir.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtpquiggod.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtijbmjwyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtttjwoekq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtmpyldnkf.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtwbkhkwux.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gthwpqjcqk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtdnxgchra.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtiybqplcz.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtyecxtpqw.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzfmfdof.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gthwlguumi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gttrazcxfs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtxzqydakp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtihanvlco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtddmusgwh.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtmgmhogvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtvxdwqwfd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtrisugzpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtvxevkdkx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtuuujkmmi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtpvdlfaau.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gthcdqekuu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafpfpcta.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcqcvjwv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtnurbmzaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwllptyy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtywetcgmo.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtedhgjaxd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtgmfqgdos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gtvvjplpul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtqcqihrma.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtgxxapkai.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtrhfpyiwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtijzktsjs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtkzeourvt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gtdeizrvtr.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtmnluulgo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtspxmgype.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtqhprkqnz.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtevovxxsz.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtdrczlyya.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtvbfzmzgk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtlclazzbz.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtaoubloxp.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtdazesibm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpvwwrkkt.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtaxwhpamj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwyvxlnba.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gthfwoxtwz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtjlrhbtfb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtpopzewjy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtmroqkeja.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gthtjtkgaw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtitdxyngj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtcphfqqhh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gtgsilgnaq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdsmbdrki.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgjcmoqdn.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtpnhzumls.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtwcyckydd.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtbsqzdlxs.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtprfmaiuv.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtilgvsdem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtvfhogwrd.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gttlfgdkcx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtvdaonpye.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtgcbcadxe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtplesvcvb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtgkfazujr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtvnzxnwwn.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtfjmmqbcs.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtktjrhsra.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtlxooadbe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtagwikcyw.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gthybwlmsj.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtibvfrdxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtzroxfhif.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtakvgwwxh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtzhubemcq.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtzpwiespt.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtvmduryaz.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtzmwuzkha.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gttgxemkng.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtitvhdsbq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtstpynuwu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtjabmirla.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkqrczos.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtcgnefcmv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtvxboiksf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtmfhnpfem.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtdcrdryvo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtlqwoakfp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriodhxac.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gtnjvburjx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtjbfktdpi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtswwnupvh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtwscllzlr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtknlwvnhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtemdjikqf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfidrfjq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gthemxawpr.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtihjpgnph.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtbyemgcsp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtvdizywba.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gthfvuizdf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmbxkbfb.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtijkaozrg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtmhglzaia.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtmbzreaua.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtzcskmfnz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtoijthapo.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtcoxxxnrb.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtdlpsbjgz.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtiwsrgsjv.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtspyfypij.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtxoxlxztz.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtvquorzct.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtaigxwtxf.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtwmmhagye.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gteoemkylm.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtvcdjlywk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtezestorw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtgktmmvob.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtgebubxxd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtmbgwcavc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtneqejhxh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtifjzkegv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtjvuoyesd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtlcufqgxd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtvobsbdzf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtyyrqzrld.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtgmwnnmtm.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtsvkifdfa.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtrglqhubx.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtyzhdtkwc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtzteqcino.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyusnafni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtrfyowayn.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtekssxgwl.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtbyzbusub.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gthesztezy.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxddjidyu.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtblrxjgzb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtlhzlcydr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtbbmbtnig.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtozejbobm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtlavwgtub.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gttxqajiqk.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtxhupcoms.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtukxhdtri.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtszvwwllj.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtvejwwdpi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtalnlwotg.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtdofeiror.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gthsdtnvsf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gthjgrzwkd.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtbvupijvo.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gtzgxazmny.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtcbxxiavp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtnwhqaxat.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqlqencm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaenuvul.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtkmvungnl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtfoprdrxt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gthedrbvyr.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gtjymbihla.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrwlcvnu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtrjcwocva.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtunfjduxt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtlvjblzef.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtbkzyhaeh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqxlhqba.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjabkjmzh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtdathveyh.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtfkpmyztl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpcxhnja.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtidibmiyn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtavdtmxbb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtlhaobiij.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gttfoeyzzz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgixyaafm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjbindhx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtameyupwt.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtzejfeuub.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtzydmlcfh.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtycmwjwqw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtkxfjjbbw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtaklvrfdu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbwllpeq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtdtzxxsxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqplzdwc.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtumjqmlez.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtdsxkijai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtelxcrytb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtandzvhqs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gthykejwgm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtgjpdufuw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtosdhfxmo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtergkfulu.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtarfxdtwn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtmmrjundj.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtmhgfgvgc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtnvvcjplv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtvbzooxca.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtolyczbud.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtqdqyidgi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtofvazrgd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtomhlusua.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtvggqgqnx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtmuwyqspx.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtwrncrvsb.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtbuleksld.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtevvfuuuw.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gteyjshbwd.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtidnhsdsq.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gttvuxdzbv.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtydcgjjbi.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtgewlimiw.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtwjekquuw.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gthympzbie.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtofjftzab.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtlmdubxpe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpxwcczwf.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtzfqfofrs.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtigbqqkhv.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtspkamhmp.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwirodreb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtcmhmpztc.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtohmjuajc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtiirshrbq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtnnmoreln.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtnecxhfkx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtebrqhseb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdewmryvs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtrrqjzsrq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxytgrgl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtoefptgua.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtglmnepsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtsuelzfyv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtsudaqvwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtyjiafqyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtpudebymu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtcvqfmhxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtvdpcbtfq.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtyxpgdszm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtjziisjqr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfwfskhvf.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtvtdaewbk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrrtbigom.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtpxtdyspa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtzodhauhk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtjbmbqoyy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtilgpzhnz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtqnqooilr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtdwqivysb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gthoqjzipq.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtiorkpnyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gttmgpnbin.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtautiyacf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtdytcpjkh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtstmqbgyh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcbjhngxf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtrtjnrgkw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gttvclkgoh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtbkuvyjjq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtqhiytoqo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwzwjgfcc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtsaihdmtr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtvzgvgisn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtaarullmf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtiwrrdqfl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtpazudvnx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtngcvbrth.html


<!-- 参考信息 -->