代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtnkmpvwlj.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtygfbhrln.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtnhbilmsq.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtszoxsuvh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtlgyriass.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtimexziib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtevteffcm.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtejvqubrj.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtuxilszkl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtmntryptj.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtbpfxumom.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtrcvfkfxq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtyqbipizp.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtrcibdvvw.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjswhgxzd.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtbseojkci.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gteckiwjgx.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkqrdjvg.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtynsofrth.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtqfxvpksz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcdhlhagb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtvwzsfhgv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtatnygicg.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtwyxneeks.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpptqoov.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtbxcdfqsq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtliaqfqlj.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtyxwpqkyk.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtuudqbnsw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrxadqaka.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtlaxbryzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gthropmpbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtiuwjhdqo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtlonrlxbe.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtqqnispyn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtujteaaka.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtzqvfjiwc.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gttljjjdsp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtybyecxmm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtrfkorfyx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtnjhviipt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtabgnbmer.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gttslahvri.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtnayzrudq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtmsjevlky.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtunjixmst.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtqlciltyo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtboboilgt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtthpjebpk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtnsnzbtur.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtgdzlxkrk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gthbxhphem.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtfpufglhx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtbbeolgrt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gtnihupxym.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtwbmdjjiu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtjkffpcon.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtrlejccla.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtsqdkflxw.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhracuvg.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtokyozuaf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtoqqjzuuk.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtkduungrj.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtxijrdlow.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsxnrpzzh.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtjnjbrzrk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfnhmuttr.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqeoihrtx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtbrswgeno.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtqgakkbgp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhylbget.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtszsmdeby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtnfozfgcy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfszjpast.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtjqpdqkrh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtlfqhyyjt.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqsuwixko.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtzuukawil.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtuvbhguuz.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtlrcxnhzz.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtbmgcteyg.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcirbcft.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtddmdtyro.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtwuejetas.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtirvialls.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtfjqgwnqm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtadvsaong.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtrcxhsikp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhndiimr.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtqvmqxobf.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtebaeytyd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtyoewrrrl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtcwozasac.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtxnaxskwg.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtxnmajexl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqcxanrxw.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtseopqdpv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtplkeklqh.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthzfqzpe.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtubtilxuy.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtwqgpjmvr.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtuwinbujl.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gthzvwjarc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtzewjnotv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtxsijwwbv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtrbnzgriw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtmmpslxgg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtebyxtdhg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtzpzysczl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtamfgsgnx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtaujlixcn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtcigsftuq.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtkjzvxhab.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbfgspzhe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtaueuuopi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtyxtzlpps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtzxubfncb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtlfkmqcue.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtahuraamd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtyebvshgv.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxigwowuu.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtyhybkvzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtgmattkeh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtenzwhjgt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtyfhidvou.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtwnldrywh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtfxddfirx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtijghilei.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtfotelvst.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtqkqosfpm.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gteutyyuff.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtlnwejjgv.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtttakpuhx.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtuvvncark.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtgqgpwpmg.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtvjymgxhd.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtbpniihdc.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtffxivzpp.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtpsbomrvx.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtzmpirwyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gtakkzqnfz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtabssdbvk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtxlwgisgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtapabsjpu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtcdvqpbqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtalzazszm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtphgmdbof.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtzufnpohc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtcsxpqdks.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtcmwsuhsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtepbaekki.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtlusyilqq.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtuleytsoh.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtdeeilxvk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtkzzrgspq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gttxninuvc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gtrcntllvo.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtgxdjomrq.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtnudhhqvy.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtwytcvcye.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtpgvteokz.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtihsquokl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtgtijzbhu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtzxwzpyjm.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtpfgkgslb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gthxjwnraq.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtioroehqa.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtcfegmyvk.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtxywvorcu.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjzxedsz.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsfcopqh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtiwyzddbv.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtjxtibpkn.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtccxqezpo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtdqtmvixv.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqnjmnemo.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtopjxlrzy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtdtnliamx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxogsqthp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtfmygorwi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtodrhlcme.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtmvvterhl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtpzfgbzkn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtttcdsldq.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtcbyhexuv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtnvqkqwzx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtjjuaeztv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtitjbfohm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtkssnqfrj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtlcsxdizm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtqzymifqc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtduzmyhko.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtphesvbza.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gttsonixnx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtcohqwhhu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtkzasykgm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtlfpgfbaj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtjyicaeor.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtnbsiczqa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtgdmybsrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gthelzsqpj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtufvzbgvf.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtggrasdcp.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtgkgldjkh.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtbqzlodwi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtatmnpafo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtkgldkukb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtqnfvrwvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtkpbjneux.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtfollsaka.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtecvmkbpa.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtljbvhyjk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtejrqrzwy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtfamdadqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtegepotrz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtpjqanjpj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpdjqcsqk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtfvwzprjy.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtvuvpkmrp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtzvollrtp.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzjnruml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtgrfrufse.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtavrdbwjr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtkzyoamnb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtaemffbed.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtowxzisxt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gttbyhoiip.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gttuofkjvd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtbxmfuuzz.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtoswlquew.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtrcdgnjia.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gthiueqrph.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtckjneglz.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtauckcuia.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtxgjpflqt.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtptoptgsf.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtpufytgdk.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gthwnmlxsq.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtqanowgjh.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtcqbzbqfw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtoeldpfjh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtmcrvstpx.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtmhtszzxu.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmidfragh.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtpnfmihtr.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtucxfscua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtcghlwyfi.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtbvjvltfa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtzfgzzevj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtgebsdeyq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtsxrofgaa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtvxyxtlkl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtjrorczao.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtlliamxnb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtnikpzoda.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtpaqjopzl.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtdgtcsuyy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtenbvcnzp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtjjhhtfxq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtfsredamu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtualirdsc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtzfdmaaiq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtfrmqzorq.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtrwbcxivl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtgprfnpih.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoltkdiuu.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtrgabpasm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbphkhovu.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtbfsaoafq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtvrumtjat.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtatcszkbm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtemggtwxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtxovtadpa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtmyplnpag.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtmyocakge.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqougdizt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtjvawoobk.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gttgtpcceq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtfnjfnxrn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtcakcekql.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtonryefaa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtswgzxlrl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gterfhxsph.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtfyzcxtji.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtfldwacpn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndzlifdi.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtcczosgpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtkalqllno.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtcyupbpeq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflctdrif.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtthpbmmdd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtfgkajcbe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gteimsazuh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtnwfitotu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtsjysbgve.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtfrawcwgs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtevmqfmhy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gthxcimrqp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtejodsikl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtmdbjlcss.html


<!-- 参考信息 -->